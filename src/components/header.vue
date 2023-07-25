<template>
    <div>
        <h3>Keterangan : {{ text }}</h3>
        <!-- <MyComponent nama="fitri" umur="16"></MyComponent> -->
    </div>
</template>

<script>
// import MyComponent from './MyComponent.vue'

// export default {
//     components :{
//         MyComponent
//     }
// }
export default {
    name:'header',
    props:['text'],
}
</script>

<style>
h3 {
    color: black;
    background-color: white;
    align-items: center;
}

</style>