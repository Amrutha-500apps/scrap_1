<template>
  <div class="hello">
    <p> Amrutha</p>
    <child></child>
    <Question></Question>
    <Table></Table>
    <cd></cd>
  </div>
</template>
<script>

//import child from '../components/Q4'
//import Question from'../components/Q1'
//import Table from'../components/Q2'
//import cd from '../components/Q6'
export default {
  name: 'HelloS33',
  components:{
    child,
    Question,
    Table,
    cd,
  },
  props :{
    Name:String
   }
}
</script>
