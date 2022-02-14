<template>
    <div>
       <p class="mb-0">Name: {{name}}</p>
       <p>Email: {{email}}</p>
    </div>
</template>

<script>
    export default {
        props:["name","email"]
    }
</script>

<style lang="scss" scoped>

</style>