<template>
  <div class="hello">
    hello world
    <first></first>
    <second></second>
    <amm></amm>
    <h1>string</h1>
    <!-- Add "scoped" attribute to limit CSS to this component only -->
  </div>
</template>

<script>
import first from '../first.vue'
import second from '../second.vue'
import amm from './amm.vue'
export default {
  name: 'HelloWorld',
  components :{
    first,
    second,
    amm,
  },
  props: {
    msg: String
  }
}
</script>


<style scoped>

</style>
