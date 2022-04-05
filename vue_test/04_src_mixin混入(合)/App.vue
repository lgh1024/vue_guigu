<template>
  <div>
    <Student name="李四" sex="女" :age="18"/>
    <hr>
    <Student name="王四" sex="男" :age="22"/>
  </div>
</template>

<script>
// 引入School组件
import Student from './components/Student.vue'
export default {
  name: 'App',
  // eslint-disable-next-line vue/no-unused-components
  components:{Student},
}
</script>

<style>

</style>