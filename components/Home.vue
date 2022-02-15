<template>
<dir>
    <h1>Hello from Home Component</h1>
     <button> Hy Bilal</button>
    </dir>
</template>
<script>
export default {
     name:"Home",
     props:{
         data:String,
         msg:String

     },methods:
     {
        hello(data)
        {
           alert(data)            
        }         
     }
        
    
}
</script>



