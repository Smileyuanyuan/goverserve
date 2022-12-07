<template>
  <div id="app">
    <!-- <Header></Header> -->
   <Register></Register>
    <!-- <Home></Home> -->
    <!-- <Personal></Personal> -->
    <!-- <Identity></Identity> -->
    <!-- <Remark></Remark> -->
    <!-- <Progress></Progress> -->
    <!-- <Footer></Footer> -->
  </div>
</template>

<script>
import Home from './views/Home'
import Register from './views/Register'
import Personal from './views/Personal'
import Header from './components/Header'
import Footer from './components/Footer'
import Identity from './views/Identity'
import Remark from './views/Remark'
import Progress from './views/Progress'

export default {
  name: 'App',
  components: {
    Home,
    Register,
    Personal,
    Header,
    Footer,
    Identity,
    Remark,
    Progress
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  position: relative;
  margin-left: auto;
  margin-right: auto;
  width: 1540px;
  height: 1000px;
}
</style>
