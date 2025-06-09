<template>
  <div>
    <HeaderComponent title="Hello title properties!" age="28" city="Odesa"/>
  </div>
  <MessageComponent title="Привіт, Vue!" message="Я вмію створювати компоненти із пропсами!" />
</template>

<script>
import HeaderComponent from "./components/Header.vue";
import MessageComponent from "./components/MessageComponent.vue";

export default {
  name: 'App',
  components: {
    HeaderComponent,
    MessageComponent
  }
}
</script>

<style>

</style>
