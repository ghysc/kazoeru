<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
    <header>
      Header
    </header>

    <main>
      Main
    </main>

    <footer>
      Footer
    </footer>
</template>

<style>
:root {
  line-height: 1.6;
  font-family:
    Inter,
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    Oxygen,
    Ubuntu,
    Cantarell,
    'Fira Sans',
    'Droid Sans',
    'Helvetica Neue',
    sans-serif;
  font-size: 15px;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

body {
  margin: 0px;
}

#app {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

header, footer {
  background-color: var(--color-1);
  padding: 10px;
  background-image: url("./pattern.jpg");
  background-blend-mode: multiply;
  background-size: 100%;
}

main {
  flex: 1;
}
</style>
