<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <UserCard nick="romashka" name="Иван Иванович Иванов" adres="Москва, Юбилейная 50" mail="coldrabbit48@example.com" phone="8-999-999-99-99"/>
  </div>
</template>

<script>
import UserCard from './components/UserCard.vue'

export default {
  name: 'App',
  components: {
    UserCard
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
