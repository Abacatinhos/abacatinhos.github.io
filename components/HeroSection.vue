<template>
  <section class="hero">
    <div class="info">
      <h1 class="abacatinhos-title">Abacatinhos.dev</h1>

      <p>
        Uma oportunidade para pessoas interessadas na área de DevRel ou
        começando nela. Assim sendo, podemos bater um papo sobre a área,
        esclarecer dúvidas e criar um plano de ação em conjunto.
      </p>
    </div>
    <img
      src="images/abacatinhos-logo.webp"
      alt="Logo da Acabatinhos, um abacate sorrindo"
      class="logo"
    />
  </section>
</template>

<script>
export default {
  name: 'HeroComponent',
}
</script>

<style>
.hero {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
.logo,
.abacatinhos-title,
p {
  margin: 0.5em 0;
}
.logo {
  width: 25%;
}
.hero > p {
  width: 40%;
}
.hero-social-links {
  margin-top: 2em;
}
.info {
  width: 60%;
}
</style>
