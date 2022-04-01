<template>
    <div>
        <p>{{name}}</p>
    </div>
</template>
<script>
import reg from '@/components/reg'
export default{
    name:'hloA3',
    components :{
        reg,
    },
    props: {
        name:String
    }
}
</script>
