<template>
  <div>
    <section id="section1">
      <h2>The outline-color Property</h2>
      <p>The outline-color property is used to set the color of the outline.</p>

      <p class="ex1-section1">A solid red outline.</p>
      <p class="ex2-section1">A dotted blue outline.</p>
      <p class="ex3-section1">An outset grey outline.</p>
    </section>
    <section id="section2">
      <h2>The outline-color Property</h2>
      <p>
        The color of the outline can also be specified using a hexadecimal value
        (HEX):
      </p>

      <p class="ex1-section2">A solid red outline.</p>
      <p class="ex2-section2">A dotted blue outline.</p>
      <p class="ex3-section2">A solid grey outline.</p>
    </section>
    <section id="section3">
      <h2>The outline-color Property</h2>
      <p>The color of the outline can also be specified using RGB values:</p>

      <p class="ex1-section3">A solid red outline.</p>
      <p class="ex2-section3">A dotted blue outline.</p>
      <p class="ex3-section3">A solid grey outline.</p>
    </section>
    <section id="section4">
      <h2>The outline-color Property</h2>
      <p>The color of the outline can also be specified using HSL values:</p>

      <p class="ex1-section4">A solid red outline.</p>
      <p class="ex2-section4">A dotted blue outline.</p>
      <p class="ex3-section4">A solid grey outline.</p>
    </section>
  </div>
</template>

<script>
export default {
  name: "OutlineColor",
};
</script>

<style scoped>
.ex1-section1 {
  border: 2px solid black;
  outline-style: solid;
  outline-color: red;
}

.ex2-section1 {
  border: 2px solid black;
  outline-style: dotted;
  outline-color: blue;
}

.ex3-section1 {
  border: 2px solid black;
  outline-style: outset;
  outline-color: grey;
}

.ex1-section2 {
  border: 2px solid black;
  outline-style: solid;
  outline-color: #ff0000; /* red */
}

.ex2-section2 {
  border: 2px solid black;
  outline-style: dotted;
  outline-color: #0000ff; /* blue */
}

.ex3-section2 {
  border: 2px solid black;
  outline-style: solid;
  outline-color: #bbbbbb; /* grey */
}

.ex1-section3 {
  border: 2px solid black;
  outline-style: solid;
  outline-color: rgb(255, 0, 0); /* red */
}

.ex2-section3 {
  border: 2px solid black;
  outline-style: dotted;
  outline-color: rgb(0, 0, 255); /* blue */
}

.ex3-section3 {
  border: 2px solid black;
  outline-style: solid;
  outline-color: rgb(187, 187, 187); /* grey */
}

.ex1-section4 {
  border: 2px solid black;
  outline-style: solid;
  outline-color: hsl(0, 100%, 50%); /* red */
}

.ex2-section4 {
  border: 2px solid black;
  outline-style: dotted;
  outline-color: hsl(240, 100%, 50%); /* blue */
}

.ex3-section4 {
  border: 2px solid black;
  outline-style: solid;
}
</style>