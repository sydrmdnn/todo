<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" class="logo">
    <TodoList/>
  </div>
</template>

<script>
import TodoList from '@/components/TodoList.vue'

export default {
  name: 'home',
  components: {
    TodoList
  }
}
</script>

<style>
.logo {
  display: block;
  margin: 20px auto;
  height: 60px;
}
</style>
