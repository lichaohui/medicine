<template>
  <div id="app">
    <router-view/>
		<cfooter></cfooter>
  </div>
</template>

<style>
#app {
  max-width: 1440px;
	margin: 0 auto;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>

<script>
import cfooter from '@/components/footer/index.vue'
export default {
  name: 'App',
	created() {
	},
	methods: {
	},
	components: {
	  cfooter
	}
}
</script>
