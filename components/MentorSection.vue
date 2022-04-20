<template>
  <section id="mentora" class="mentor-section">
    <div class="info">
      <h1>Sobre a Mentora</h1>
      <p>
        A mentora da Abacatinhos.dev é a
        <a href="https://polywork.com/pachicodes" target="_blank">PachiCodes</a
        >, Developer Advocate no Github, co-fundadora da
        <a href="https://Feministech.github.io" target="_blank">Feministech</a>,
        produtora de conteúdo e streamer.
      </p>
    </div>

    <img
      src="images/pachicodes.webp"
      alt="Pachi com um cabelo de raiz preta e fios verdes, óculos e de casaco, com um leve sorriso de um lado do rosto"
      class="logo"
    />
  </section>
</template>

<script>
export default {
  name: 'mentorSection',
}
</script>

<style>
.mentor-section {
  justify-content: space-around;

  background-color: whitesmoke;
  display: flex;
  flex-direction: row;
  align-items: center;
  text-align: left;
}

.info > h1,
strong {
  color: var(--darkGreen);
}

.logo {
  border-radius: 7%;
}
</style>
