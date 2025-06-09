<template>
  <div>
    <HeaderComponent title="Hello title properties!" age="28" city="Odesa"/>
  </div>
  <HelloWorld msg = "Тут буде заголовок" />
</template>

<script>
import HeaderComponent from "./components/Header.vue";
import HelloWorld from "./components/HelloWorld.vue";


export default {
  name: 'App',
  components: {
    HeaderComponent,
    HelloWorld
  }
}
</script>

<style>

</style>
