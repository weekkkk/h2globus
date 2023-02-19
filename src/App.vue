<script lang="ts" setup></script>

<template>
  <h1>test</h1>
</template>

<style lang="scss">
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}
html {
  font-size: var(--n-fs-p);
  color: var(--n-base);
}

body {
  font-family: 'Open Sans', sans-serif;
  line-height: var(--n-lh-regular);
  display: flex;
  min-height: 100vh;
}

#app {
  width: 100%;
  display: flex;
  flex-direction: column;
}

.container {
  max-width: 1180px;
  width: 100%;
}

a {
  text-decoration: none;
  transition: 0.15s;
}

ul,
li {
  list-style: none;
  text-decoration: none;
}
</style>
