<template>
    <div id="app">
        <h1>{{ msg }}</h1>
        <a>Test</a>
    </div>
</template>

<script>
  export default {
    name: 'app',
    data () {
      return {
        msg: 'Welcome to Your Vue.js App',
      }
    },
  }
</script>

<style lang="scss">
    #app {
        font-family: Tahoma, Arial, Helvetica, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        color: #aaa;
        background-color: #666;
    }

    h1, h2 {
        font-weight: normal;
    }

    ul {
        list-style-type: none;
        padding: 0;
    }

    li {
        display: inline-block;
        margin: 0 10px;
    }

    a {
        color: #97f;
    }
</style>
