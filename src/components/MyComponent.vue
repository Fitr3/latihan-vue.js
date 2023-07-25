<template>
    <div>
        <b>Nama saya {{ nama }}</b>
        <br>
        <b>Umur saya {{ umur }}</b>
    </div>
</template>

<script>
// import MyComponent from './MyComponent.vue'

export default {
    props: ['nama','umur']
}
</script>

<style>
h1{
    color: blue;
}
p{
    size: 16px;
}
</style>