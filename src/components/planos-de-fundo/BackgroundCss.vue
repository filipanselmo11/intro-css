<template>
  <div>
    <h1>Olá mundo</h1>
    <p>
        Essa página está com a cor azul de fundo.
    </p>
    <div>
        <h1>Exemplo de background-color CSS</h1>
        <div>
            Isso é um texto dentro do elemento div
        </div>
        <p>
            Este parágrafo tem seu próprio background-color.
        </p>
        Ainda estamos no elemento div.
    </div>
    <div>
        <h1>
            Caixas Transparentes
        </h1>
        <p>
            Quando a propriedade de opacidade é usada para adicionar transparência
            ao fundo de um elemento, todos os elementos filhos também ficam transparentes.
            Isso pode fazer o text dentro do elemento transparente difícl de ler.
        </p>
        <div class="first">
            <h1>opacity 0.1</h1>
        </div>
        <div class="second">
            <h1>opacity 0.3</h1>
        </div>
        <div class="third">
            <h1>opacity 0.6</h1>
        </div>
        <div>
            <h1>Opacity 1 (default)</h1>
        </div>
    </div>
    <div>
        <h1>
            Caixas Transparentes 2
        </h1>
        <p>
            Resultado com opacidade:
        </p>
        <div style="opacity: 0.1;">
            <h1>10% de opacidade</h1>
        </div>
        <div style="opacity: 0.3;">
            <h1>30% de opacidade</h1>
        </div>
        <div style="opacity: 0.6;">
            <h1>60% de opacidade</h1>
        </div>
        <div>
            <h1>Opacidade 1</h1>
        </div>
        <p>
            Resultado com rgba():
        </p>
        <div class="primeiro">
            <h1>10% de opacidade</h1>
        </div>
        <div class="segundo">
            <h1>30% de opacidade</h1>
        </div>
        <div class="terceiro">
            <h1>60% de opacidade</h1>
        </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'BackgroundCss'
}
</script>

<style scoped>
/* div {
    background-color: lightblue;
} */

/* h1 {
    background-color: green;
}

div {
    background-color: lightblue;
}

p {
    background-color: yellow;
} */

/* div {
    background-color: green;
}

.first {
    opacity: 0.1;
}

.second {
    opacity: 0.3;
}

.third {
    opacity: 0.6;
} */

.primeiro {
    background: rgba(0, 128, 0, 0.1);
}

.segundo {
    background: rgba(0, 128, 0, 0.3);
}

.terceiro {
    background: rgba(0, 128, 0, 0.6);
}

</style>