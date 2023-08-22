<template>
<!-- <h1 v-if="show">heloo</h1>
<h1 v-else>else</h1>

<button @click="show=!show"> toggle</button> -->
<!-- <ul>

    <li v-for="itmes in tecnology" :key="itmes" >{{ itmes }}</li>
</ul> -->


<ul>
    <li v-for="item in users" :key="item.age">
        {{item?.name}}
    </li>
</ul>
</template>
 
<script>
export default{

name:"ifelsecondition.vue",

data(){

  return { 


    // tecnology:['java','javascript','node']
    users:[
        {name:'emon',age:'33'},
        {name:'sumon',age:'34'},
        {name:'alif',age:'35'},
    ]
}

}
}
</script>