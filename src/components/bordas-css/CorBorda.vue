<template>
  <div>
    <div>
      <h2>The border-color Property</h2>
      <p>This property specifies the color of the four borders:</p>

      <p class="one">A solid red border</p>
      <p class="two">A solid green border</p>
      <p class="three">A dotted blue border</p>

      <p>
        <b>Note:</b> The "border-color" property does not work if it is used
        alone. Use the "border-style" property to set the borders first.
      </p>
    </div>
    <div>
      <h2>The border-color Property</h2>
      <p>
        The border-color property can have from one to four values (for the top
        border, right border, bottom border, and the left border):
      </p>

      <p class="um">A solid multicolor border</p>
    </div>
    <div>
      <h2>The border-color Property</h2>
      <p>
        The color of the border can also be specified using a hexadecimal value
        (HEX):
      </p>

      <p class="hex-one">A solid red border</p>
      <p class="hex-two">A solid blue border</p>
      <p class="hex-three">A solid grey border</p>
    </div>
    <div>
      <h2>The border-color Property</h2>
      <p>The color of the border can also be specified using RGB values:</p>

      <p class="rgb-one">A solid red border</p>
      <p class="rgb-two">A solid blue border</p>
      <p class="rgb-three">A solid grey border</p>
    </div>
    <div>
      <h2>The border-color Property</h2>
      <p>The color of the border can also be specified using HSL values:</p>

      <p class="hsl-one">A solid red border</p>
      <p class="hsl-two">A solid blue border</p>
      <p class="hsl-three">A solid grey border</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "CorBorda",
};
</script>

<style scoped>
.one {
  border-style: solid;
  border-color: red;
}

.two {
  border-style: dotted;
  border-color: green;
}

.three {
  border-style: dotted;
  border-color: blue;
}

.um {
  border-style: solid;
  border-color: red green blue yellow; /** red top, green right, blue bottom and yellow left */
}

.hex-one {
  border-style: solid;
  border-color: #ff0000;
}

.hex-two {
  border-style: solid;
  border-color: #0000ff;
}

.hex-three {
  border-style: solid;
  border-color: #bbbbbb;
}

.rgb-one {
  border-style: solid;
  border-color: rgb(255, 0, 0);
}

.rgb-two {
  border-style: solid;
  border-color: rgb(0, 0, 255);
}

.rgb-three {
  border-style: solid;
  border-color: rgb(187, 187, 187);
}

.hsl-one {
  border-style: solid;
  border-color: hsl(0, 100%, 50%); /* red */
}

.hsl-two {
  border-style: solid;
  border-color: hsl(240, 100%, 50%); /* blue */
}

.hsl-three {
  border-style: solid;
  border-color: hsl(0, 0%, 73%); /* grey */
}
</style>