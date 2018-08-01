<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: '模板首页！'
    }
  }
}
</script>
