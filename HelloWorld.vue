<template>
  <div class="hello">
  <child3 ref="message">{{message}}</child3>
  <child message="hlo" name="amrutha" number=12345></child> 
  <child1 :message="message" :name="name" :number="number"></child1>
  <button @click="fun()">click me!</button>
    </div>
</template>
<script>
import child from '@/components/child.vue'
import child1 from '@/components/proj.vue'
import child3 from '@/components/child3.vue'
   export default{
     name:'parentcomponentA2',
        components:{
          child,
          child1,
          child3,
        },
    data(){
      return{
        message:'hlo',
        name:'amrutha',
        number:'1234',
        number1:'1264'
      }
    },
   methods:{
     fun(){
       this.$ref.message.f1();
     }
   }
}
</script>
