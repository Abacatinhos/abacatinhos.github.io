<template>
  <section id="participar" class="join-section">
    <h1>Como Participar</h1>
    <p>
      O primeiro passo é ler o nosso
      <a
        href="https://github.com/Abacatinhos/codigo-de-conduta"
        target="_blank"
      >código de conduta</a> e
      <strong>aceitar todas as regras, práticas</strong> e valores no nosso documento, e depois,
      <a
        href="https://calendly.com/pachicodes/mentoria-devrel"
        target="_blank"
      >agendar um bate papo com a Pachi</a>.
    </p>

    <p>Depois disso, você receberá um convite para entrar no Servidor do Discord.</p>
  </section>
</template>

<script>
export default {
  name: "JoinSection"
}
</script>

<style>
.join-section {
  background-color: white;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: left;
}
.join-section > h1,
strong {
  color: var(--darkGreen);
}
</style>

