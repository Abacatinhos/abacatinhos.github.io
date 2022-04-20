<template>
  <section id="sobre" class="about-section">
    <h1>Sobre a mentoria</h1>

    <p>A abacatinhos.dev é o nosso grupo de mentoria sobre a área de Devrel!</p>

    <p>
      A nossa missão é
      <strong
        >aumentar o conhecimento e prática das pessoas participantes da mentoria
        sobre a área de Devrel</strong
      >, podendo explorar e se especializarem na área mais ainda.
    </p>
  </section>
</template>

<script>
export default {
  name: 'AboutSection',
}
</script>

<style>
.about-section {
  background-color: white;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: left;
}
.about-section > h1,
strong {
  color: var(--darkGreen);
}
</style>
