<template>
    <div>
        <input type="text" name="email" id="email" placeholder="E-mail"><br>
        <input type="text" name="nome" id="nome" placeholder="Nome"><br>
        <button>Teste</button>
        <router-view />
    </div>
</template>

<script>
export default{
    created(){
        
    },
    data(){
        return {
            
        }
    }   
}
</script>
