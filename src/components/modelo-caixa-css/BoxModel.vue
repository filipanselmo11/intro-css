<template>
  <div>
    <section id="section1">
      <h2>Demonstrating the Box Model</h2>

      <p>
        The CSS box model is essentially a box that wraps around every HTML
        element. It consists of: borders, padding, margins, and the actual
        content.
      </p>

      <div class="div-section__1">
        This text is the content of the box. We have added a 50px padding, 20px
        margin and a 15px green border. Ut enim ad minim veniam, quis nostrud
        exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        Duis aute irure dolor in reprehenderit in voluptate velit esse cillum
        dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
        proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </div>
    </section>
    <section id="section2">
      <h2>Calculate the total width:</h2>

      <img src="klematis4_big.jpg" width="350" height="263" alt="Klematis" />
      <div class="div-section__2">
        The picture above is 350px wide. The total width of this element is also
        350px.
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "BoxModel",
};
</script>

<style scoped>
.div-section__1 {
  background-color: lightgrey;
  width: 300px;
  border: 15px solid green;
  padding: 50px;
  margin: 20px;
}

.div-section__2 {
  width: 320px;
  padding: 10px;
  border: 5px solid gray;
  margin: 0;
}
</style>