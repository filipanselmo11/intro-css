<template>
  <div>
    <div>
      <h2>The border Property</h2>

      <p>
        This property is a shorthand property for border-width, border-style,
        and border-color.
      </p>
    </div>
    <div>
      <h2>The border-left Property</h2>
      <p>
        This property is a shorthand property for border-left-width,
        border-left-style, and border-left-color.
      </p>
    </div>
    <div>
      <h2>The border-bottom Property</h2>
      <p>
        This property is a shorthand property for border-bottom-width,
        border-bottom-style, and border-bottom-color.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "AbreviacaoBorda",
};
</script>

<style scoped>
/* p {
  border: 5px solid red;
} */

/* p {
  border-left: 6px solid red;
  background-color: lightblue;
} */
p {
    border-bottom: 6px solid red;
    background-color: yellow;
}
</style>