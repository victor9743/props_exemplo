<template>
    <div id='cliente'>
       
        <h4>Nome: {{ nome }}</h4>
        
        <p>Número: {{ numero }}</p>
        <p>Email: {{ email }}</p>
        <hr>
       
    </div>
</template>
<script>
export default {

    data(){
        return{
           
          
        }
    },
    props:{

        nome: String,
        numero: Number,
        email: String,
      
    }
    
}
</script>