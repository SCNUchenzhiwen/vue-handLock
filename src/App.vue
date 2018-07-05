<template>
  <div id="app">
    <img src="./assets/logo.png">
    <p>{{handLock}}</p>
    <button @click="errorDraw">绘制错误显示</button>
    <vHandLock @getHandLock="getHandLock" @clear="reset" ref="handLock"></vHandLock>
  </div>
</template>

<script>
  import HelloWorld from './components/HelloWorld'
  import {vHandLock} from './components/handLock'

  export default {
    name: 'App',
    components: {
      HelloWorld,
      vHandLock
    },
    data () {
        return {
            handLock: ''
        }
    },
    methods: {
      getHandLock (data) {
          this.handLock = data
      },
      reset () {
          console.log('reset')
      },
      errorDraw () {
          this.$refs.handLock.errorDraw()
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
    color: #ffffff;
    background: url("./assets/timg.jpg") no-repeat center top;
    background-size: auto 100%;
    height: 100%;
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }

  body {
    height: 100%;
    width: 100%;
    margin: 0;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
  }
</style>
