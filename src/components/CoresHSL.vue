<template>
  <div>
    <h1>Cores Específicas usando valores HSL</h1>
    <div>
        <h2>hsl(0, 100%, 50%)</h2>
        <h2>hsl(240, 100%, 50%)</h2>
        <h2>hsl(147, 50%, 47%)</h2>
        <h2>hsl(300, 76%, 72%)</h2>
        <h2>hsl(39, 100%, 50%)</h2>
        <h2>hsl(248, 53%, 58%)</h2>
    </div>
    <h1>Saturação HSL</h1>
    <p>
        O segundo parâmetro do hsl define a saturação.
        Menos saturação significa menos cor.
        0% é completamente cinza.
    </p>
    <div>
        <h1>hsl(0, 100%, 50%)</h1>
        <h1>hsl(0, 80%, 50%)</h1>
        <h1>hsl(0, 60%, 50%)</h1>
        <h1>hsl(0, 40%, 50%)</h1>
        <h1>hsl(0, 20%, 50%)</h1>
        <h1>hsl(0, 0%, 50%)</h1>
    </div>
    <h1>Luminosidade HSL</h1>
    <p>
        O terceiro parâmetro do hsl() define a luminosidade. 0% significa preto,
        e 100% significa branco.
    </p>
    <div>
        <h2>hsl(0, 100%, 0%)</h2>
        <h2>hsl(0, 100%, 25%)</h2>
        <h2>hsl(0, 100%, 75%)</h2>
        <h2>hsl(0, 100%, 90%)</h2>
        <h2>hsl(0, 100%, 100%)</h2>
    </div>
    <h1>Tons de Cinza</h1>
    <p>
        Com HSL, tons de cinza são feitos definindo a saturação para 0%,
        e ajustando a luminosidade de 0% a 100%
    </p>
    <div>
        <h2>hsl(0, 0%, 0%)</h2>
        <h2>hsl(0, 0%, 24%)</h2>
        <h2>hsl(0, 0%, 47%)</h2>
        <h2>hsl(0, 0%, 71%)</h2>
        <h2>hsl(0, 0%, 94%)</h2>
        <h2>hsl(0, 0%, 100%)</h2>
    </div>
    <h1>Fazendo cores transparentes com HSLA</h1>
    <div>
        <h2>hsla(9, 100%, 64%, 0)</h2>
        <h2>hsla(9, 100%, 64%, 0.2)</h2>
        <h2>hsla(9, 100%, 64%, 0.4)</h2>
        <h2>hsla(9, 100%, 64%, 0.6)</h2>
        <h2>hsla(9, 100%, 64%, 0.8)</h2>
        <h2>hsla(9, 100%, 64%, 1)</h2>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>