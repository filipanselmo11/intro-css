<template>
  <div>
    <h1>The background Property</h1>

    <p>
      The background property is a shorthand property for specifying all the
      background properties in one declaration.
    </p>

    <p>
      Here, the background image is only shown once, and it is also positioned
      in the top-right corner.
    </p>

    <p>
      We have also added a right margin, so that the text will not write over
      the background image.
    </p>
    <div>
        <h1>Todas as propriedades de plano de fundo Css</h1>
        <div>
            <h1>background</h1>
            <p>
                Define todas as propriedades do plano de fundo em uma declaração
            </p>
        </div>
        <div>
            <h1>background-attachment</h1>
            <p>
                Define se uma imagem de fundo é fixa ou rola com o resto da página
            </p>
        </div>
        <div>
            <h1>background-clip</h1>
            <p>
                Especifica a área de pintura do plano de fundo
            </p>
        </div>
        <div>
            <h1>background-color</h1>
            <p>
                Define a cor de fundo de um elemento
            </p>
        </div>
        <div>
            <h1>background-image</h1>
            <p>
                Define a imagem de fundo para um elemento
            </p>
        </div>
        <div>
            <h1>background-origin</h1>
            <p>
                Especifica onde a(s) imagem(ns) de fundo está(ão) posicionada(s)
            </p>
        </div>
        <div>
            <h1>background-position</h1>
            <p>
                Define a posição inicial de uma imagem de fundo
            </p>
        </div>
        <div>
            <h1>background-repeat</h1>
            <p>
                Define como uma imagem de fundo será repetida
            </p>
        </div>
        <div>
            <h1>background-size</h1>
            <p>
                Especifica o tamanho das imagens de fundo
            </p>
        </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'AbreviacaoFundo'
};
</script>

<style scoped>
div {
    background: #FFFFFF url('img_tree.png') no-repeat right top; /**Propriedade abreviada */
    margin-right: 200px;
}
</style>