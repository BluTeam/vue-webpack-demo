<template lang="slm">
#app
  img class="logo" src="./assets/logo.png"
  hello
  p Welcome to your Vue.js app!
  p
  p
    | To get a better understanding of how this boilerplate works, check out
    a href="http://vuejs-templates.github.io/webpack" target="_blank" its documentation
    | .
    | It is also recommended to go through the docs for
    a href="http://webpack.github.io/" target="_blank" Webpack
    | and
    a href="http://vuejs.github.io/vue-loader/" target="_blank" vue-loader
    | .
    | If you have any issues with the setup, please file an issue at this boilerplate's
    a href="https://github.com/vuejs-templates/webpack" target="_blank" repository
    | .
  p
    | You may also want to checkout
    a href="https://github.com/vuejs/vue-router/" target="_blank" vue-router
    | for routing and
    a href="https://github.com/vuejs/vuex/" target="_blank" vuex 
    | for state management.
</template>

<script lang="coffee">
Hello = require('./components/Hello')

module.exports = {
  components: {
    hello: Hello
  }
}

console.log 1
</script>

<style lang="sass">

html
  height: 100%

body
  display: flex
  align-items: center
  justify-content: center
  height: 100%

#app
  color: #2c3e50
  margin-top: -100px
  max-width: 600px
  font-family: Source Sans Pro, Helvetica, sans-serif
  text-align: center

#app a
  color: #42b983
  text-decoration: none

.logo
  width: 100px
  height: 100px

</style>
