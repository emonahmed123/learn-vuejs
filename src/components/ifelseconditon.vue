<template>
<h1 v-if="show">heloo</h1>
<h1 v-else>else</h1>

<button @click="show=!show"> toggle</button>
</template>

<script>
export default{

name:"ifelsecondition.vue",

data(){

  return { show:false
}

}
}
</script>