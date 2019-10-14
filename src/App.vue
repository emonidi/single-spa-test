<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    <AddTodo></AddTodo>
  </div>
</template>

<script>
import AddTodo from "./components/AddTodo";

export default {
  name: "App",
  components: {
    AddTodo
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
