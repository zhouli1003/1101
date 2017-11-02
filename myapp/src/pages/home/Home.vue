<template>
  <div>
      <index-header />
  </div>
</template>

<script>

	import Header from "./Header.vue";

	export default {
	    name: 'HelloWorld',
	    data () {
	    	return {
	            msg: 'Home'
	        }
	    },
	    components: {
	    	"index-header": Header	
	    }
	}
</script>

<style scoped>

</style>
