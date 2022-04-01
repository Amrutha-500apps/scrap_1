<template>
  <div class="hello">
    <h2> using props for static input</h2>
    <ch message='hlo' name='amrutha' number=12345></ch>
    <h2> using props for dynamic input</h2>
    <ch :message='message1' :name='name1' :number='number1'></ch>
    <h2> using ref</h2>
    <ch msg="hlooo" ref="ref" message="hlo" name="amrutha" number="12345"></ch>
    <button @click="fun()">click me</button>
  </div>
</template>
<script>
import ch from '@/components/ch.vue'
export default {
  name:'childsA2',
  components :{
    ch,
  },
  props:{
    message:String,
    name:String,
    number:Number,
  },
      data(){
       return{
        message1:'hlo',
        name1:'amrutha',
        number1:'1234',
        }
      },
      methods:{
        fun(){
          this.$refs.ref.f1();
        }
      }
}
</script>

    
