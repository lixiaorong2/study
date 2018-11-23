<template>
  <div id="app">
    <HelloWorld/>
    <Header/>
    <Swliper/>
    <Signup/>
    <objectpk/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import Header from './components/Header'
import Swliper from './components/Swliper'
import Signup from './components/Signup'
import objectpk from './components/objectpk'

export default {
  name: 'App',
  components: {
    Header,
    Swliper,
    Signup,
    objectpk
  }
}
</script>

<style>

</style>
