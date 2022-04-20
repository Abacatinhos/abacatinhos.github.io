<template>
  <section id="devrel" class="devrel-section">
    <h1>O que é DevRel?</h1>
    <p>
      DevRel é um campo interdisciplinar em tecnologia que se concentra em
      <strong>criar, nutrir e apoiar</strong> o relacionamento entre uma empresa
      ou produto e pessoas desenvolvedoras ou comunidades de pessoas
      desenvolvedoras.
    </p>

    <p>
      Então o objetivo de uma pessoa DevRel é
      <strong>produzir conteúdo, engajar e cativar</strong> as pessoas a
      consumirem produtos de empresas de tecnologia, aproximando assim essas
      duas partes que normalmente são tão separadas.
    </p>
  </section>
</template>

<script>
export default {
  name: 'DevrelSection',
}
</script>

<style>
.devrel-section {
  background-color: whitesmoke;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: left;
}
.devrel-section > h1,
strong {
  color: var(--darkGreen);
}
</style>
