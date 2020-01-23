<template>
  <div id="app">
    {{msg}}
    <todo-list />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import TodoList from "./components/TodoList.vue";
export default Vue.extend({
  components: {
    TodoList
  },
  data: function() {
    return {
      msg: "hello" as string
    };
  }
});
</script>>

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
