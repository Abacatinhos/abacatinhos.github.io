<template>
  <div class="app">
    <Header />
    <HeroSection />
    <AboutSection />
    <MentorSection />
    <JoinSection />
    <Footer />
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

<style>
/* Color palettes */
:root {
  --green: #1e9111;
  --lightGreen: #6ac700;
  --darkGreen: #264700;
  --blue: #2a067a;
}
/* General styles */
div.app {
  width: 100vw;
  height: 100vh;
}
* {
  margin: 0;
  padding: 0;
  border: 0;
  outline: 0;
  vertical-align: baseline;
  background: transparent;
  font-family: "Rubik", sans-serif;
  font-size: 100%;
}
section {
  padding: 10vh 10vw;
}
/* Default font styles */
h1,
h2,
h3 {
  font-family: "Poppins", sans-serif;
  color: var(--darkGreen);
}
h1 {
  font-size: 4ch;
}
h2 {
  font-size: 3ch;
}
h3 {
  font-size: 2.5ch;
}
p,
a,
strong {
  font-size: 2ch;
}
h1,
h2,
h3,
strong,
a {
  font-weight: 700;
  text-decoration: none;
}

a {
  color: var(--blue);
}

a:hover {
  transition: 0.2s;
  text-decoration: underline;
}
p {
  font-weight: 400;
  width: 100%;
}
</style>
