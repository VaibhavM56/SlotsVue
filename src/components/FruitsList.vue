<template>
  <section>
    <base-card>
      <h2>Fruits List</h2>
      <template v-slot:personal>
        <ul>
          <li>apple</li>
          <li>mango</li>
          <li>grapes</li>
          <li>Litchi</li>
        </ul>
      </template>
    </base-card>
  </section>
</template>

<script>
export default {};
</script>

<style>
ul {
  list-style: none;
}
</style>
