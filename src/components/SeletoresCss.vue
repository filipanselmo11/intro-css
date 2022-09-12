<template>
  <div>
    <p>Todo paragrafo vai ser afetado pelo estilo.</p>
    <!-- <p id="param1">Eu também</p> -->
    <p>E eu também.</p>
    <p id="para1">Olá Mundo</p>
    <p>
        Este parágrafo não é afetado pelo estilo.
    </p>
  </div>
</template>

<script>
export default {
    name: 'SeletoresCss',
}
</script>

<style scoped>
/* p {
    text-align: center;
    color: red;
} */
#para1 {
    text-align: center;
    color: red;
}
</style>