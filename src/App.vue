<template>
  <div>
    <HeaderComponent title="Hello title properties!" age="28" city="Odesa"/>
  </div>
</template>

<script>
import HeaderComponent from "./components/Header.vue";

export default {
  name: 'App',
  components: {
    HeaderComponent,
  }
}
</script>

<style>

</style>
