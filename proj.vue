<template>
    <div> 
        <p>content:{{message}}</p>
        <p>name:{{name}}</p>
        <p>number:{{number}}</p>
    </div>
</template>
<script>
export default {
    name:'childA3',
    props :{
        message:String,
        name:String,
        number:Number,
    },
     methods :{
         f1(){
         alert("successful")
         }
     }    
}
</script>