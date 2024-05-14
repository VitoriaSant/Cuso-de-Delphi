<template>


<div 

    v-for="obj in array
    v-bind:key="obj.id" 
"> 
//Precisa colocar uma key para identificar o obj e a impressao ser mais rapido e com menos recursos
//v-bind e para indicar que o "obj.id" e do array e náo uma string qualquer
    {{ obj.name}}
</div>

    
</template>
<script>
import Nome from 'caminho';

export default{
    name: 'App'
    components: {
        Nome
    }
},
data(){
    return{
        Variaveis //Tudo declarado aqui fica disponivel para ser usado no componente 
    }
}


</script>
<style >

</style>
