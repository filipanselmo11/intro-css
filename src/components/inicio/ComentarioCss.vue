<template>
  <div>
    <p>
        Olá Mundo
    </p>
    <p>
        Este parágrafo está estilizado com css.
    </p>
    <p>
        Comentários no css não serão apresentados na saída.
    </p>
  </div>
</template>

<script>
export default {
    name: 'ComentarioCss',
}
</script>

<style scoped>
/* Isso é um comentário* */
p {
    color: red !important; /* A cor do texto está setada em vermelho* */
}
/*
    Isso é um comentário de multi-linha
* */
</style>