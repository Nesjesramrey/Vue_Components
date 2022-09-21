<template>
  <div>
    <ModalOne/>
  </div>
</template>

<script>
import ModalOne from "./components/Modal-one.vue";


export default {
  name: "App",
  components: { ModalOne },
  data() {
    return {
      show: false,
    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>
