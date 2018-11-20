<template>
  <h1 class="masthead">
    <strong>
      <slot></slot>
    </strong>
  </h1>
</template>

<script>
export default {
  name: 'Masthead',
};
</script>

<style scoped lang="scss">
@import '@/assets/scss/palette.scss';
@import '@/assets/scss/typography.scss';

.masthead {
  font-family: $serif-font-stack;
  font-weight: 400;
  color: $masthead-text;
  font-size: 3rem;
  text-align: left;
  width: 50vw;
  line-height: 1.3;
  margin-top: 0px;
  margin-bottom: 15px;
}
</style>

