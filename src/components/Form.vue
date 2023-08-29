<template>
<form >
    <label >Email</label>
    <input type="text" v-model="form.email" placeholder="enter email"><br/>
    <label >password</label>
     <input type="password" v-model="form.password" placeholder="enter password">
<button @click="login()" type="button">login</button>
</form>
</template>



<script>
export default{
    name:"From.vue",

    data(){
        return{
        form: {
        email:'',
        password:''
       }}
    },
    methods:{
        login(){
           console.log("logdata",this.form) 
        }
    }
}
</script>