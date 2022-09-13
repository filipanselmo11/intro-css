<template>
  <div>
    <h2>The border-width Property</h2>
    <p>This property specifies the width of the four borders:</p>

    <p class="one">Some text.</p>
    <p class="two">Some text.</p>
    <p class="three">Some text.</p>
    <p class="four">Some text.</p>
    <p class="five">Some text.</p>
    <p class="six">Some text.</p>

    <p>
      <b>Note:</b> The "border-width" property does not work if it is used
      alone. Always specify the "border-style" property to set the borders
      first.
    </p>
    <div>
      <h2>The border-width Property</h2>
      <p>
        The border-width property can have from one to four values (for the top
        border, right border, bottom border, and the left border):
      </p>

      <p class="um">Some text.</p>
      <p class="dois">Some text.</p>
      <p class="tres">Some text.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "LarguraBorda",
};
</script>

<style scoped>
.one {
  border-style: solid;
  border-width: 5px;
}

.two {
  border-style: solid;
  border-width: medium;
}

.three {
  border-style: dotted;
  border-width: 2px;
}

.four {
  border-style: dotted;
  border-width: thick;
}

.five {
  border-style: double;
  border-width: 15px;
}

.six {
  border-style: double;
  border-width: thick;
}

.um {
    border-style: solid;
    border-width: 5px 20px; /**5px top and bottom, 20px on the sides */
}

.dois {
    border-style: solid;
    border-width: 20px 5px; /** 20px top and bottom, 5px on the sides */
}

.tres {
    border-style: solid;
    border-width: 25px 10px 4px 35px; /** 25px top, 10px right, 4px bottom, 35px left */
}
</style>