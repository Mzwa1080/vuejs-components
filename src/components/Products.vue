<template>
    <div>
        <h2>Child component</h2>
        <p>{{ greetings }}</p>
    </div>
</template>

<script>
    export default {
        name : 'ProductsComp',
        props : ['greetings']
    }
</script>

<style scoped>

</style>