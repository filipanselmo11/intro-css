<template>
  <div><!--Nome de cores CSS-->
    <h1 style="background-color: Tomato;">
        Tomate
    </h1>
    <h1 style="background-color: Orange;">
        Laranja
    </h1>
    <h1 style="background-color: DodgerBlue;">
        DodgerBlue
    </h1>
    <h1 style="background-color: MediumSeaGreen;">
        MediumSeaGreen
    </h1>
    <h1 style="background-color: Gray;">
        Gray
    </h1>
    <h1 style="background-color: StateBlue;">
        StateBlue
    </h1>
    <h1 style="bakground-color: Violet;">
        Violet
    </h1>
    <h1 style="background-color: LightGray;">
        LightGray
    </h1>
    <div><!--Cor de Fundo Css--->
        <h1 style="background-color: DodgerBlue;">
            Olá Mundo
        </h1>
        <p style="background-color: Tomato;">
            Lorem ipsum dolor sit amet, consectuer adipiscing...
        </p>
    </div>
    <div><!---Cor do texto Css-->
        <h3 style="color: Tomato;">
            Olá Mundo
        </h3>
        <p style="color: DodgerBlue;">
            Lorem ipsum dolor sit amet, consectetuer adipiscing elit...
        </p>
        <p style="color: MediumSeaGreen;">
            Ut wisi enim ad minim veniam, quis nostrud exercu tation...
        </p>
    </div>
    <div><!---Cor da borda CSS--->
        <h1 style="border: 2px solid Tomato;">
            Olá Mundo
        </h1>
        <h1 style="border: 2px solid DodgerBlue;">
            Olá Mundo
        </h1>
        <h1 style="border: 2px solid Violet;">
            Olá Mundo
        </h1>
    </div>
    <div> <!--Valores de cores Css--->
        <p>
            Mesmo nome "Tomato":
        </p>
        <h1 style="background-color: rgb(255, 99, 71);">
            rgb(255, 99, 71)
        </h1>
        <h1 style="bcakground-color: #ff6347;">
            #ff6347
        </h1>
        <h1 style="background-color: hsl(9, 100%, 64%);">
            hsl(9, 100%, 64%)
        </h1>
        <p>
            Mesmo nome "Tomato", mas 50% transparente.
        </p>
        <h1 style="background-color: rgba(255, 99, 71, 0.5);">
            rgba(255, 99, 71, 0.5)
        </h1>
        <h1 style="bakground-color: hsla(9, 100%, 64%, 0.5);">
            hsla(9, 100%, 64%, 0.5)
        </h1>
        <p>
            Além de adicionar o nome predefinido das cores, cores podem ser especificadas
            usando RGB, HEX, HSL, ou até cores transparentes usando valores como RGBA
            ou HSLA.
        </p>
    </div>
  </div>
</template>

<script>
export default {
    name: 'CoresCss',
}
</script>

<style scoped>

</style>