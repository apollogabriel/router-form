<template>
    <h1>Job Details</h1>
    <p>This is the ID {{ $route.params.id }}</p>
</template>
<script>
export default{
    data(){
        return{
            id: this.$route.params.id
        }
    }
}
</script>
<style></style>