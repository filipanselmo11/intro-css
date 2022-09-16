<template>
  <div>
    <section id="section1">
      <h2>CSS height and width properties</h2>

      <div class="div-section__1">
        This div element has a height of 50 pixels and a width of 100%.
      </div>
    </section>
    <section id="section2">
      <h2>Set the height and width of an element</h2>

      <div class="div-section__2">
        This div element has a height of 200px and a width of 50%.
      </div>
      <div class="other-div-section__2">
        This div element has a height of 100px and a width of 500px
      </div>
    </section>
    <section id="section3">
      <h2>Set the max-width of an element</h2>

      <div class="div-section__3">
        This div element has a height of 100px and a max-width of 500px.
      </div>

      <p>Resize the browser window to see the effect.</p>
    </section>
  </div>
</template>

<script>
export default {
  name: "WidthHeight",
};
</script>

<style scoped>
.div-section__1 {
  height: 50px;
  width: 100%;
  border: 1px solid #4caf50;
}

.div-section__2 {
  height: 200px;
  width: 50%;
  background-color: powderblue;
}

.other-div-section__2 {
  height: 100px;
  width: 500px;
  background-color: powderblue;
}

.div-section__3 {
  max-width: 500px;
  height: 100px;
  background-color: powderblue;
}
</style>