<template>
  <user-details :userData="userData" />
  <fruits-list />
</template>

<script>
import FruitsList from "./components/FruitsList.vue";
import UserDetails from "./components/UserDetails.vue";
export default {
  name: "App",
  components: {
    UserDetails,
    FruitsList,
  },
  data() {
    return {
      userData: {
        name: "himagirisha",
        description: "im a SDE",
        role: "admin",
      },
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
