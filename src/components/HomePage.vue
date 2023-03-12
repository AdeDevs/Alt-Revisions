<template>
    <div>
        <h1>Counter: {{ count }}</h1>
        <input type="text" name="count" id="myCount"><br>
        <button type="submit">Submit</button>

        <br>
        <button @click="increment">Increment</button>
        <button @click="decrement">Decrement</button>
        <button @click="reset">Reset</button>
    </div>
</template>


<script>
export default {
    name: "HomePage",
    data() {
        return {
            count: 0,
        }
    },
    props: {
        msg: String,
    },
    methods: {
        increment() {
            this.count++
        },
        decrement() {
            this.count--
        },
        reset() {
            this.count = 0
        }, 
    },
}
</script>