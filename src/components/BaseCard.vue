<template>
  <div>
    <slot></slot>

    <body class="body1">
      <slot name="personal"></slot>
    </body>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
div {
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.3);
  border-radius: 10px;
  max-width: 30rem;
  background-color: rgb(232, 166, 42);
  color: whitesmoke;
}
.body1 {
  background-color: blueviolet;
  color: cornsilk;
  border-radius: 10px;
  margin-top: 18px;
}
</style>
