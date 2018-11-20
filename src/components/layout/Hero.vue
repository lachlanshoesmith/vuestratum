<template>
  <header class="hero">
    <slot></slot>
  </header>
</template>

<script>
export default {
  name: 'Hero',
};
</script>

<style scoped lang="scss">
@import '@/assets/scss/palette.scss';

.hero {
  background: $gradient;
  padding-top: 5vh;
  padding-bottom: 5vh;
  padding-left: 5vw;
}
</style>

