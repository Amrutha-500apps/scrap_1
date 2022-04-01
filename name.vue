<template>
    <div>
        <p>{{message}}
    </div>
</template>
<script>
export default {
    name:'hlo', 
    props:{
        name:String,
    },  
    data(){
        return{
            name:"mantra"
        }
    },
      methods: {
        change_name(){
            this.name = "agile";
        }
    }  
    
}
</script>
