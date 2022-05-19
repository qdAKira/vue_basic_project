<template>
  <div>
    <School></School>
    <Student></Student>
  </div>
</template>

<script>
//引入组件
import Student from './Student.vue'
import School from './School.vue'
export default {
  name:'App',
  comments:{
    School,
    Student
  }
}
</script>

