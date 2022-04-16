<template>
  <div class="child">
    <h3>我是Child组件（子）</h3>
    <Son></Son>
  </div>
</template>

<script>
  // import {inject} from 'vue'
  import Son from './Son.vue'
  export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name: 'Child',
    components: {Son}
    /* setup(){
			let x = inject('car')
			console.log(x,'Child-----')
		} */
  }
</script>

<style>
	.child{
		background-color: skyblue;
		padding: 10px;
	}
</style>