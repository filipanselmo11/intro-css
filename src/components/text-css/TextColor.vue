<template>
  <div>
    <section id="text-color">
      <h1>This is heading 1</h1>
      <p>
        This is an ordinary paragraph. Notice that this text is blue. The
        default text color for a page is defined in the body selector.
      </p>
      <p>Another paragraph.</p>
    </section>
    <section id="text-color-background">
      <h1>This is a Heading</h1>
      <p>This page has a grey background color and a blue text.</p>
      <div>This is a div.</div>
    </section>
  </div>
</template>

<script>
export default {
  name: "TextColor",
};
</script>

<style scoped>
body {
  color: blue;
}

h1 {
  color: green;
}

#text-color-background {
    background-color: lightgrey;
    color: blue;
}

h1 {
    background-color: black;
    color: white;
}

div {
    background-color: blue;
    color: white;
}
</style>