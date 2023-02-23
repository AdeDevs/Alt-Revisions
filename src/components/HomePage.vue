<template>
    <div>
        <h1>{{ page }}</h1>
        <p>{{ msg }}</p>
    </div>
</template>

<script>
export default {
    name: "HomePage",
    data() {
        return {
            page: "Home Page",
            msg: String
        }
    }
}
</script>