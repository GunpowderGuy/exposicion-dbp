<template>
    <div>      
        <label>User: </label>
        <input type="text" :value="user" @input="onUsernameInput">
        
        <br><br>

        <label>Password: </label>
        <input type="password" :value="password" @input="onPasswordInput">

        <br><br>

        <button @click="onSubmit" :value="usuario">Submit</button>

        <br><br><br>

        <div>
            <p v-if="acceso" class="access">Bienvenid@, {{this.usuario}}</p>
            <p v-else class="error">Ingrese su usuario</p>
        </div>
    </div>
</template>


<script>
export default {
  name: 'NuxtLogin',
  data(){
    return {
        user:'',
        password:'',
        acceso:false,
        usuario:''
    }
  },

  methods:{
    onUsernameInput(e){
        this.user=e.target.value;
    },

    onPasswordInput(e){
        this.password=e.target.value;
    },

    onSubmit(){
        this.acceso=true;
        sessionStorage.setItem('user',this.user);
        this.user='';
        this.password='';
        this.usuario=sessionStorage.getItem('user');
    }
  }
}
</script>


<style scoped>
.error{
    color:red;
}

.access{
    color:green;
}
</style>