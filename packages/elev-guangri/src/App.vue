<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <p>elev-guangri</p>
  <Test />
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Test from '@elev/standard/src/components/Test.vue'

export default defineComponent({
  name: 'App',
  components: {
    Test
  }
})
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
