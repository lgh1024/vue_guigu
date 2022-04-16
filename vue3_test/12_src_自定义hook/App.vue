<template>
  <button @click="isShowDemo = !isShowDemo">却换隐藏/显示</button>
  <Demo v-if="isShowDemo"></Demo>
  <hr>
  <Test></Test>
</template>

<script>
  import {ref} from 'vue'
  import Demo from './components/Demo.vue'
  import Test from './components/Test.vue'
  export default {
    name: 'App',
    components: {Demo, Test},
    setup() {
      let isShowDemo = ref(true)
      // 返回一个对象（常用）
      return {
        isShowDemo
      }
    }
  }
</script>