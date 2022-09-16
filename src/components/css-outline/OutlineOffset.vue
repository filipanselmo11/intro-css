<template>
  <div>
    <section id="sec1">
      <h2>The outline-offset Property</h2>

      <p class="p-sec1">
        This paragraph has an outline 15px outside the border edge.
      </p>
    </section>
    <section id="sec2">
      <h2>The outline-offset Property</h2>

      <p class="p-sec2">
        This paragraph has an outline of 15px outside the border edge.
      </p>
    </section>
  </div>
</template>

<script>
export default {
  name: "OutlineOffset",
};
</script>

<style scoped>
.p-sec1 {
  margin: 30px;
  border: 1px solid black;
  outline: 1px solid red;
  outline-offset: 15px;
}

.p-sec2 {
  margin: 30px;
  background: yellow;
  border: 1px solid black;
  outline: 1px solid red;
  outline-offset: 15px;
}
</style>