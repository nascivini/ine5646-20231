<template>
  <form>
    <div>
    <label for="username">Usuário</label>
    <input id="username" type="text" v-model="username" />

    <label for="password">Senha</label>
    <input id="password" type="text" v-model="password" />
  </div>
  <div>
    <button type="submit">
      Entrar
    </button>
  </div>
  </form>
</template>
<script>
export default {
  name: 'Login',
  data() {
    return {
      username: '',
      password: '',
    }
  }
}
</script>