<script setup>
import { ref } from "vue";

const pessoa = ref({
  nome: '',
  sobrenome: '',
  email: '',
  senha: '',
  cidade: '',
  estado: '',
  datanascimento: '',
  hobbies: [],
  preferenciadLinguagem: ''
})



</script>
 
<template>
    <div class="">
        <div>
            <label for="">nome</label>
            <input type="text" v-model="nome"  id="">
        </div>
        <div>
            <label for="">sobrenome</label>
            <input type="text" v-model="sobrenome">
        </div>
        <div>
            <label for="">email</label>
            <input type="email" v-model="email">
        </div>
        <div>
            <label for="">senha</label>
            <input type="password" v-model="senha">
        </div> 
        <div>
            <label for="">data de nascimento</label>
            <input type="date" v-model="datanascimento">
        </div>   
        <div>
            <input type="radio" v-model="hobbies">
            <label for="">esportes</label>
            <label for="">musicas</label>
            <label for="">viagens</label>

        </div>
        <div>
            <label for="">preferencia de linguagem</label>
            <input type="#" v-model="preferenciadLinguagem">
        </div>
    </div>
</template>

<style>
.container{
    display: flex;
    column-gap: 2rem;
    flex-direction: row;
}
</style>