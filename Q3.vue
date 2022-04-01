<template>
    <div>
        <p>local variables</p>
    </div>
</template>
<script>
import child2 from './components/child2'
export default{
    name:'local',
    components :{
        child2,
    },
    props:{
        name:String,
    }
}
</script>
