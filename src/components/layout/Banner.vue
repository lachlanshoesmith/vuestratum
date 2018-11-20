<template>
  <div class="banner" :class="type">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'Banner',
  props: {
    type: {
      type: String,
      required: false,
    },
  },
};
</script>

<style scoped lang="scss">
@import '@/assets/scss/palette.scss';

.banner {
  background: $gradient;
  padding-top: 1vh;
  padding-bottom: 1vh;
  padding-left: 5vw;
  padding-right: 5vw;
}

.danger {
  background: $red-gradient;
  color: $lighter-text;
}
</style>

