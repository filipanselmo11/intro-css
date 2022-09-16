<template>
  <div>
    <section id="section1">
      <h2>The outline-width Property</h2>

      <p class="ex1">A thin outline.</p>
      <p class="ex2">A medium outline.</p>
      <p class="ex3">A thick outline.</p>
      <p class="ex4">A 4px thick outline.</p>
    </section>
    <section id="section2">

    </section>
  </div>
</template>

<script>
export default {
    name: 'OutlineWidth',
};
</script>

<style scoped>
.ex1 {
  border: 1px solid black;
  outline-style: solid;
  outline-color: red;
  outline-width: thin;
}

.ex2 {
  border: 1px solid black;
  outline-style: solid;
  outline-color: red;
  outline-width: medium;
}

.ex3 {
  border: 1px solid black;
  outline-style: solid;
  outline-color: red;
  outline-width: thick;
}

.ex4 {
  border: 1px solid black;
  outline-style: solid;
  outline-color: red;
  outline-width: 4px;
}
</style>