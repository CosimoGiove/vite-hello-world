<script>
export default {
    name: "AppTitle",
    data(){
        return{
            titolo: "il mio primo titolo con vite "
        }
    }
}
</script>

<template>
 <h1>{{ titolo }}</h1>
</template>

<style scoped >
h1{
    color: red;
}
</style>