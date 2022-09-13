<template>
  <div style="background-color: lavender;">
    <link rel="stylesheet" type="text/css" href="meuEstilo.css">
    <h1>
        Múltiplos Estilos serão casqueados em um ?
    </h1>
    <p>
        Aqui, a cor de fundo da página está com o Css inline,
        e também com o css interno e também com o css externo.
    </p>
    <p>
        Experimente remover os estilos para ver como o casqueamento
        funciona (tente remover o css inline primeiro,
        depois o interno e depois o externo).
    </p>
  </div>
</template>

<script>
export default {
    name: 'CssCascata',
}
</script>

<style scoped>
div {
    background-color: linen;
}
</style>