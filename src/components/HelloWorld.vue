
<template>
  <button @click="tab='java'" >java</button>
  <button @click="tab='node'"  >node</button>
  <button @click="tab='php'"  >php</button>
  <component :is="tab"/>
</template>

<script >
import java from "./java.vue";
import node from "./node.vue";
import php from "./php.vue";

export default{
  name:"HelloWorld"
  ,
  components:{
    java,node,php,
  },
  data(){
     return{
      tab:'Java'
     }
  },
}
</script>
