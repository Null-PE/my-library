<template>
  <div id="app">
    <Header />
  </div>
  <router-view/>
</template>

<script>
import Header from './components/Header.vue'

export default{
  name: 'App',
  components: {
    Header
  }
}
</script>
