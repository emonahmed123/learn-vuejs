<template>
    
     <h1>Get Cheakbox and Radio Button Valu</h1>
    
     <h3>Technology</h3>
     <label for="javaScript"> javaScript</label>
      <input type="checkbox"   v-model="tecnology" id="javaScript" value="javaScript">
     <label for="php"> php</label>
      <input type="checkbox" value="php" id="php" v-model="tecnology" >
     <h4>selectd tecno{{ tecnology }}</h4>
    
    </template>
    
    
    
    
    <script>
    export default{
        name:'Cheakbox.vue',
    
    
    data(){
    
            return{
                tecnology:[]
            }
    },
    
    methods:{
    
     
    }
    
    }
    
    </script>