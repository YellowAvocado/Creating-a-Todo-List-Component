<script> 
export default {
  props: {
    todos: {
    }
  }
}
</script>

<template>

    <div>
        <p v-for="todo in todos">{{ todo }}</p>
    </div>

</template>