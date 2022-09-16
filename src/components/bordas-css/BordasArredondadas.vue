<template>
  <div>
    <div>
      <h2>The border-radius Property</h2>
      <p>This property is used to add rounded borders to an element:</p>

      <p class="normal">Normal border</p>
      <p class="round1">Round border</p>
      <p class="round2">Rounder border</p>
      <p class="round3">Roundest border</p>
    </div>
    <div>
      <h1>Border-Top</h1>
      <p>This is some text in a paragraph.</p>
    </div>
    <div>
      <h1>Border-Bottom</h1>
      <p class="none">No bottom border.</p>
      <p class="dotted">A dotted bottom border.</p>
      <p class="dashed">A dashed bottom border.</p>
      <p class="solid">A solid bottom border.</p>
      <p class="double">A double bottom border.</p>
      <p class="groove">A groove bottom border.</p>
      <p class="ridge">A ridge bottom border.</p>
      <p class="inset">An inset bottom border.</p>
      <p class="outset">An outset bottom border.</p>
    </div>
    <div>
      <h1>Border-left</h1>
      <p>
        <b>Note:</b> The "border-left-width" property does not work if it is
        used alone. Use the "border-style" property to set the borders first.
      </p>
    </div>
    <div>
      <h1>Color of the four borders</h1>
      <p class="one">One-colored border!</p>
      <p class="two">Two-colored border!</p>
      <p class="three">Three-colored border!</p>
      <p class="four">Four-colored border!</p>
      <p>
        <b>Note:</b> The "border-color" property does not work if it is used
        alone. Use the "border-style" property to set the borders first.
      </p>
    </div>
    <div>
        <h1>Color of the right border</h1>
        <p>This is some text in a paragraph.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "BordasArredondadas",
};
</script>

<style scoped>
.normal {
  border: 2px solid red;
  padding: 5px;
}

.round1 {
  border: 2px solid red;
  border-radius: 5px;
  padding: 5px;
}

.round2 {
  border: 2px solid red;
  border-radius: 8px;
  padding: 5px;
}

.round3 {
  border: 2px solid red;
  border-radius: 12px;
  padding: 5px;
}

/* p {
  border-style: solid;
  border-top: thick double #ff0000;
} */

/* p {
  border-style: solid;
} */

.none {
  border-bottom-style: none;
}

.dotted {
  border-bottom-style: dotted;
}

/* p {
  border-style: solid;
  border-left-width: 15px;
} */

.one {
  border-style: solid;
  border-color: #0000ff;
}

.two {
  border-style: solid;
  border-color: #ff0000 #0000ff;
}

.three {
  border-style: solid;
  border-color: #ff0000 #00ff00 #0000ff;
}

.four {
  border-style: solid;
  border-color: #ff0000 #00ff00 #0000ff rgb(250, 0, 255);
}

p {
    border-style: solid;
    border-right-color: #ff0000;
}
</style>