<template>
  <div id="app">
    <p class="app">{{msg}}</p>
    <!-- <img src="./assets/logo.png">
    <router-view/> -->
    <button @click='btnHandle'>弹出框</button>
  </div>
</template>

<script>
// export default {
//   name: 'App'
// }
import {toast} from 'mint-ui'
export default {
  name: 'hellworld',
  data () {
    return {
      msg: '====wi==='
    }
  },
  methods: {
    btnHandle() {``
      toast('提示信息')
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
