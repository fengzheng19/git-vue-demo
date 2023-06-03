<template>
  <div id="app">
    <user-demo-1/>
    <user-demo-2/>
  </div>
</template>

<script>
import userDemo1 from './components/demo1.vue'
import userDemo2 from './components/demo2.vue'

export default {
  name: 'App',
  components: {
    userDemo1,
    userDemo2
  }
}
</script>

<style>
#app {

}
</style>
