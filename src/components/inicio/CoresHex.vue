<template>
  <div>
    <h1>
        Cores Específicas usando valores HEX
    </h1>
    <div>
        <h2>#FF0000</h2>
        <h2>#0000FF</h2>
        <h2>#3CB371</h2>
        <h2>#EE82EE</h2>
        <h2>#FFA500</h2>
        <h2>#6A5ACD</h2>
    </div>
    <h1>Tons de Cinza</h1>
    <div>
        <h2>#3C3C3C</h2>
        <h2>#616161</h2>
        <h2>#787878</h2>
        <h2>#B4B4B4</h2>
        <h2>#F0F0F0</h2>
        <h2>#F9F9F9</h2>
    </div>
    <div>
        <h1>Código Hexadecimal de 3 dígitos</h1>
        <p>
            Isto é um parágrafo.
        </p>
    </div>
  </div>
</template>

<script>
export default {
    name: 'CoresHex',
}
</script>

<style scoped>
div {
    background-color: #FC9; /** igual a #FFCC99 */
}

h1 {
    color: #F0F; /** igual a #FF00FF */
}

p {
    color: #B58; /** igual a #BB5588 */
}


</style>