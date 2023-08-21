<template>
<!-- 
<input type="text" v-model="count" >
<h1>{{count}}</h1> -->


<input type="text" v-model="email" >
<br/>
<input type="text" v-model="password">

<button @click="getValues()">get values</button>
</template>




<script>
export default{
    name:'twowaydatabinding.vue',


data(){

return{
   email:null,
   password:null,

}
},

methods:{

    getValues(){
          console.log('ki khobor bondo',this.email,this.password)
          
    }
}

}

</script>