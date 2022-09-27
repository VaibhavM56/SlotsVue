<template>
  <div>
    <base-card>
      <h1>{{ userData.name }}</h1>
      <p>{{ userData.role }}</p>
      <p>{{ userData.description }}</p>

      <template v-slot:personal> hello this is v slot </template>
    </base-card>
  </div>
</template>

<script>
export default {
  props: ["userData"],
};
</script>

<style></style>
