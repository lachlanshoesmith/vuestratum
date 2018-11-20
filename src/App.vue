<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="scss">
@import './assets/scss/palette.scss';
@import './assets/scss/typography.scss';

body {
  background: $body-bg;
  font-family: $font-stack;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #333;
  margin: 0;
}

img.emoji {
  height: 1em;
  width: 1em;
  margin: 0 0.05em 0 0.1em;
  vertical-align: -0.1em;
}
</style>
