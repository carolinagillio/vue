<template>
    <h1>Meu nome é:{{ nome }} </h1>
</template>

<script>
export default {
    name:'LifeCycle',
    data(){
        return{
            nome: 'ainda não sei'
        }
    },
    created(){
        setTimeout(() =>{
            this.nome = ' Carolina'
        }, 1000)
        
    },
    mounted(){
        setTimeout(() =>{
             this.nome = 'Gustavo'
        }, 2000);
       
    }
}
</script>