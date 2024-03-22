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
    <div class="conteiner">
        <div>
            <label for="">nome</label>
            <input type="text" v-model="name"  id="">
        </div>
        <div>
            <label for="">sobrenome</label>
            <input type="text" v-model="sobrenome">
        </div>
        <div>
            <label for="">email</label>
            <input type="text" v-model="email">
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
            <label for="">hobbies</label>
            <input type="#" v-model="hobbies">
        </div>
        <div>
            <label for="">preferencia de linguagem</label>
            <input type="#" v-model="preferenciadLinguagem">
        </div>
    </div>
</template>