<template>
  <h2 class="subheading">
      <slot></slot>
  </h2>
</template>

<script>
export default {
  name: 'Subheading',
};
</script>

<style scoped lang="scss">
@import '@/assets/scss/palette.scss';
@import '@/assets/scss/typography.scss';

.subheading {
  font-family: $serif-font-stack;
  font-weight: 400;
  color: $subheading-text;
  font-size: 2rem;
  text-align: left;
  width: 60vw;
  line-height: 1.5;
  margin-bottom: 0px;
}
</style>

