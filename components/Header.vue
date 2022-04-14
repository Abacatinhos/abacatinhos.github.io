<!-- Please remove this file from your project -->
<template>
  <header>
    <strong class="header-title">Abacatinhos.dev</strong>

    <nav class="header-nav">
      <a href="#sobre" class="header-anchor">Sobre a mentoria</a>
      <strong>|</strong>
      <a href="#mentora" class="header-anchor">Sobre a mentora</a>
      <strong>|</strong>
      <a href="#participar" class="header-anchor">Como participar</a>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'HeaderComponent',
}
</script>

<style>
header {
  background-color: var(--green);
  padding: 5vh 8vw;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
}
strong {
  color: white;
}
@media screen and (min-width: 1001px) {
  header {
    padding: 5vh 8vw;
    justify-content: space-between;
  }
}
@media screen and (max-width: 1000px) {
  header {
    padding: 3vh 8vw;
    flex-direction: column;
    justify-content: space-around;
  }
}
.header-nav {
  height: 100%;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
}
.header-nav > * {
  margin: 0.3em;
}
.header-title {
  font-size: 2.5ch;
}
.header-anchor,
.header-title {
  color: white;
}
</style>
