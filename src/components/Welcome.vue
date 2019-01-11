<template>
    <div class="header">
        <h1>{{ msgOne }}</h1>
        <h2>{{ msgTwo }}</h2>
    </div>

</template>

<script>
export default {
    data() {
        return {
            msgOne: 'Welcome to my calculator app!!',
            msgTwo: 'This app was created using Vue.js'
        }
    }
}
</script>

<style scoped>
    .header {
        background-color: #111ccc;
        color: aqua;
    }
</style>