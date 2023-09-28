<script>
import TodoList from './components/TodoList.vue'
import Counter from './components/Counter.vue'

export default {
  components: {
    TodoList,
    Counter
  },
  data() {
    return {
      todos: ['Buy groceries', 'Walk the dog', 'Complete homework']
    }
  }
}

</script>

<template>

  <div>

    <h1>My Todo List</h1>
    <TodoList :todos="todos" />
    <Counter />

  </div>

</template>
