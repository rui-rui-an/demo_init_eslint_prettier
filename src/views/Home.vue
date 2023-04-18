<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <Search></Search>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Search from './Search.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Search
  },
  methods: {
    saaa () {
      const b = '1'
      if (b === 1) {
        console.log(222)
      }
      const a = 'sadasdw'
      console.log(a)
      console.log(1354321)
      console.log(1111111111)
    }
  }
}
</script>
