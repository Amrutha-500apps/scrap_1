<template>
    <div> 
        <p>msg:{{message}}</p>
        <p>name:{{name}}</p>
        <p>num:{{number}}</p>
    </div>
</template>
<script>
export default{
    name:'childsA23',
    props: {
        message:String,
        name:String,
        number:Number,       
    },
    methods:{
        f1(){
            alert("successful")
        }
    }
}
</script>
