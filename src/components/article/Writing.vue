<template>
  <article>
    <slot></slot>
  </article>
</template>

<script>
export default {
  name: 'Writing',
};
</script>

<style scoped lang="scss">
@import '@/assets/scss/palette.scss';
@import '@/assets/scss/typography.scss';

article {
  color: $body-text;
  margin-left: 5vw;
  margin-top: 5vh;
  margin-bottom: 5vh;
  width: 70vw;
  line-height: 2;
  font-size: 1.3rem;
  text-align: justify;
  h3 {
    color: $article-heading-text;
  }
  strong {
    color: $strong-text;
  }
}
</style>
