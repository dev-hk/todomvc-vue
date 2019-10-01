<template>
  <div id="app">
    <section class="todoapp">
      <Input />
      <TodoList />
      <TodoListFilter />
    </section>
    <Footer />
  </div>
</template>

<script>
import Input from "@/components/Input";
import Footer from "@/components/Footer";
import TodoList from "@/components/TodoList";
import TodoListFilter from "@/components/TodoListFilter"

export default {
  name: "app",
  components: {
    Input,
    Footer,
    TodoList,
    TodoListFilter
  }
};
</script>

<style src="../node_modules/todomvc-app-css/index.css" />
