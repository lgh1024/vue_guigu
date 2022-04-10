<template>
	<div class="container">
		<Search></Search>
		<List></List>
	</div>
</template>

<script>
import Search from './compontents/Search.vue'
import List from './compontents/List.vue'
	export default {
		name:'App',
		components: {Search, List}
	}
</script>