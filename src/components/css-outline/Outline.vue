<template>
  <div>
    <section id="section1">
      <h2>CSS Outline</h2>
      <p class="p-section__1">
        This element has a 2px black border and a green outline with a width of
        10px.
      </p>
    </section>
    <section id="section2">
      <h2>The outline-style Property</h2>

      <p class="dotted">A dotted outline</p>
      <p class="dashed">A dashed outline</p>
      <p class="solid">A solid outline</p>
      <p class="double">A double outline</p>
      <p class="groove">
        A groove outline. The effect depends on the outline-color value.
      </p>
      <p class="ridge">
        A ridge outline. The effect depends on the outline-color value.
      </p>
      <p class="inset">
        An inset outline. The effect depends on the outline-color value.
      </p>
      <p class="outset">
        An outset outline. The effect depends on the outline-color value.
      </p>
    </section>
  </div>
</template>

<script>
export default {
  name: "Outline",
};
</script>

<style scoped>
.p-section__1 {
  border: 2px solid black;
  outline: #4caf50 solid 10px;
  margin: auto;
  padding: 20px;
  text-align: center;
}

p {
  outline-color: red;
}

.dotted {
  outline-style: dotted;
}
.dashed {
  outline-style: dashed;
}
.solid {
  outline-style: solid;
}
.double {
  outline-style: double;
}
.groove {
  outline-style: groove;
}
.ridge {
  outline-style: ridge;
}
.inset {
  outline-style: inset;
}
.outset {
  outline-style: outset;
}
</style>