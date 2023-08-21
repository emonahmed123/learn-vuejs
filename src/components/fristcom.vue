<template>
    <h1>Home Compoent</h1>
    <h1>name:{{ getName() }}</h1>
    <h1>name:{{ email }}</h1>

    <button  v-on:click="test()" >Click</button>
    <button @click="count++">Add 1</button>
<p>Count is: {{ count }}</p>
</template>



<script>
  export default{
    name:'fristcom',
    
 data(){

      return {
        
        count:0           
      
      }
 },
      methods:{
        getName(){
             return this.count+1
        },

        test(){
            alert('fuctin called')

            
                   
             
         
      }
    }
  }
</script>