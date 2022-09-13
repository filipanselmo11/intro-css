<template>
  <div>
    <h1>Olá mundo</h1>
    <!-- <p>
        Imagem com plano de fundo estranho.
    </p> -->
    <!-- <p>
        Aqui, a imagem de fundo está repetindo apenas na horizontal
    </p> -->
    <p>A imagem de fundo é apresentada apenas uma vez.</p>
  </div>
</template>

<script>
export default {
  name: "BackgroundRepeat",
};
</script>

<style scoped>
/* div {
    background-image: ulr('gradient_bg.png');
    background-repeat: repeat-x;
} */

/* div {
  background-image: url("img_tree.png");
  background-repeat: no-repeat;
} */

div {
    background-image: url('img_tree.png');
    background-repeat: no-repeat;
    background-position: right top;
    margin-right: 200px;
}
</style>