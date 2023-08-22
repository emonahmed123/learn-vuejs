<template>


<ul>
    <li v-for="user in users " :key="user.name">
        <child v-bind:data="user"/>
    </li>
</ul>

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
        users:[
            {
                name:"emon",
                age:23,

            },
            {
                name:"smon",
                age:23,

            },
            {
                name:"amon",
                age:23,

            },
            {
                name:"tmon",
                age:23,

            },
        ]
    }
}
 }

</script>