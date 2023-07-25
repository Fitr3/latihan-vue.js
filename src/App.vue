<template>
  <NewComponent></NewComponent>
  <MyComponent nama="fitri" umur="16"></MyComponent>
</template>

<script>
import NewComponent from './components/NewComponent.vue';
// import MyComponent from './components/MyComponent.vue';

export default {
  name: "App",
  
  components: {
    // MyComponent,
    NewComponent
  }

}   
</script>