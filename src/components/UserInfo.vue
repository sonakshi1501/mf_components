<template>
    <div>
       <p class="mb-0">Name: {{name}}</p>
       <p>Email: {{email}}</p>
    </div>
</template>

<script>
    export default {
        props:{
            name:{
                type:String,
                required:true,
                default: "name given"
            },
            email:{
                type:String,
                required:true,
                default: "email given"
            }

        }
    }
</script>

<style lang="scss" scoped>

</style>