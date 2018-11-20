<template>
  <input class="submit-input" type="submit" :name="name" :id="name" :value="label">
</template>

<script>
export default {
  name: 'TextInput',
  props: {
    name: {
      type: String,
      required: true,
    },
    label: {
      type: String,
      required: true,
    },
  },
};
</script>

<style scoped lang="scss">
@import '@/assets/scss/palette.scss';

.submit-input {
  background: $submit-input-bg;
  color: $strong-text;
  border: none;
  padding: 10px;
  height: 64px;
  font-size: 1rem;
}
</style>

