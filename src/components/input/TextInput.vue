<template>
  <input class="text-input" type="text" :name="name" :id="name" :placeholder="placeholder">
</template>

<script>
export default {
  name: 'TextInput',
  props: {
    name: {
      type: String,
      required: true,
    },
    placeholder: {
      type: String,
      required: true,
    },
  },
};
</script>

<style scoped lang="scss">
@import '@/assets/scss/palette.scss';

.text-input {
  border: none;
  background: $text-input-bg;
  color: $body-text;
  font-size: 1.1rem;
  padding: 10px;
  height: 44px;
  &::placeholder {
    color: $light-text;
  }
}
</style>

