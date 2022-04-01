<template>
    <div> 
        <p>content:{{message}}</p>
        <p>name:{{name}}</p>
        <p>number:{{number}}</p>
    </div>
</template>
<script>
export default {
    name:'childA2',
    props :{
        message:String,
        name:String,
        number:Number,
        data:String,
    }
}
</script>
    
