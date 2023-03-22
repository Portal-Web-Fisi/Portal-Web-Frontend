<template>
    <div>
      <h1>Iniciar sesión</h1>
      <form>
        <div>
          <label for="username">Nombre de usuario:</label>
          <input type="text" id="username" v-model="username">
        </div>
        <div>
          <label for="password">Contraseña:</label>
          <input type="password" id="password" v-model="password">
        </div>
        <button type="submit" @click.prevent="login">Iniciar sesión</button>
      </form>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        username: '',
        password: '',
      }
    },
    methods: {
      login() {
        
        console.log(`Iniciar sesión con el nombre de usuario ${this.username} y la contraseña ${this.password}`);
      }
    }
  }
  </script>
  