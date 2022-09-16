<template>
  <div>
    <section id="section1">
      <h2>The outline Property</h2>

      <p class="ex1-sec1">A dashed outline.</p>
      <p class="ex2-sec1">A dotted red outline.</p>
      <p class="ex3-sec1">A 5px solid yellow outline.</p>
      <p class="ex4-sec1">A thick ridge pink outline.</p>
    </section>
  </div>
</template>

<script>
export default {
  name: "OutlineShorthand",
};
</script>

<style scoped>
.ex1-sec1 {outline: dashed;}
.ex2-sec1 {outline: dotted red;}
.ex3-sec1 {outline: 5px solid yellow;}
.ex4-sec1 {outline: thick ridge pink;}
</style>