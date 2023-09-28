<script>
export default {
    data() {
        return {
            count: 0
        }
    },
    methods: {
        increment() {
            this.count++
        },
        decrement() {
            this.count--
        }
    }
}
</script>

<template>
    <div>
        Counter: {{ count }}
        <button @click="increment">+</button>
        <button @click="decrement">-</button>
    </div>
</template>