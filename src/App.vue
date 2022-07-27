<template>
  <div id="app">
    <h1>Todos</h1>
    <todo-list-vue/>
    <form-todo-vue/>
  </div>
  
</template>

<script>
import TodoListVue from './components/TodoList.vue';
import FormTodoVue from './components/FormTodo.vue';
export default {
  name: 'App',
  components: {
    TodoListVue,
    FormTodoVue
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
