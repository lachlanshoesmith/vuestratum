<template>
  <code>
    <slot></slot>
  </code>
</template>

<script>
import highlight from 'highlight.js';
import 'highlight.js/styles/github.css';

export default {
  name: 'Snippet',
  mounted() {
    highlight.initHighlightingOnLoad();
  },
};
</script>

<style scoped lang="scss">
@import '@/assets/scss/palette.scss';
@import '@/assets/scss/typography.scss';

code {
  background: $code-bg;
  color: $code-text;
  font-family: $mono-font-stack;
  padding: 5px;
}
</style>

