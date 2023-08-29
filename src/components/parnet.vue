<template>


<!-- <ul>
    <li v-for="user in users " :key="user.name">
        <child v-bind:data="user"/>
    </li>
</ul> -->

<h1 :class="{Orange:colorfull}">css cingidng</h1>

<button @click="colorfull=!colorfull">change</button>

</template>



<script>
import child from './child.vue';
 export default{

    name:"parnet",

components:{
    child
},

data(){
    return{
      colorfull:false,
    }
}
 }

</script>


<style scoped>
.Orange{
    color: orange;
    background-color: aqua;
}
</style>