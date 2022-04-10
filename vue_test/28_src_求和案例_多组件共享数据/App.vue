<template>
	<div>
		<Count></Count>
		<Person></Person>
	</div>
</template>

<script>
	import Count from './compontents/Count.vue'
	import Person from './compontents/Person.vue'
		export default {
			name:'App',
			components: {Count, Person},
			
		}
</script>