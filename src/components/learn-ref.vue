<template>
    <h1>hello</h1>
<input type="text" ref="input">
 <button @click="getDat">click</button>
</template>

<script>

export default{
    name:"learn-ref",

    methods:{
        getDat(){
             this.$refs.input.focus()
        }
    }
}
</script>