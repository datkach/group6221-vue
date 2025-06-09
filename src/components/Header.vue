<template>
<header>
<h1>{{ title }} {{ age }}</h1>
<p>{{ city }}</p>
</header>
</template>

<script>
export default {
    name: "HeaderComponent",
    props: {
        title :{
            type: String,
            required: true
        },
        age : {
            type: Number,
            default: 50
        },
        city: String,
    }
};
</script>

<style scoped>
header {
    background: #42b983;
    color: white;
    padding: 15px;
    text-align: center;
}
</style> 