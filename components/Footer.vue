<template>
  <footer>
    <nav class="footer-nav">
      <a
        href="https://github.com/Abacatinhos/codigo-de-conduta"
        class="footer-anchor"
        target="_blank"
        >Código de Conduta</a
      >
      <hr class="divider solid" />
      <a href="#sobre" class="header-anchor">Sobre a mentoria</a>
      <a href="#mentora" class="header-anchor">Sobre a mentora</a>
      <a href="#participar" class="header-anchor">Como participar</a>
    </nav>

    <div class="right-col">
      <h2 class="footer-title">Abacatinhos.dev</h2>
      <strong class="made-with">Feito com 💚</strong>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'footerComponent',
}
</script>

<style>
footer {
  background-color: var(--darkGreen);
  padding: 5vh 8vw;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: baseline;
}
.footer-nav > a {
  text-align: left;
}
.footer-nav,
.right-col {
  display: flex;
  flex-direction: column;
  gap: 0.3em;
}
.footer-social-links {
  display: flex;
  flex-direction: row;
  margin-bottom: 0.2em;
  align-items: baseline;
}
.made-with {
  display: flex;
  flex-direction: column;
  height: 30%;
}
.footer-anchor,
.footer-title,
.made-with {
  color: white;
  text-align: right;
}
.divider {
  border-top: 3px solid white;
}
</style>
