<template>
  <div class="text-and-submit-inputs">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'TextSubmitInputs',
};
</script>

<style scoped lang="scss">
@import '@/assets/scss/palette.scss';

.text-and-submit-inputs {
  display: flex;
  height: 64px;
}
</style>

