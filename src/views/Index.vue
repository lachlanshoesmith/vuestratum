<template>
  <div class="index">
    <hero>
      <masthead>Welcome to Vuestratum!</masthead>
      <subheading><em>Vuestratum</em> is a thorough, component-packed
      boilerplate for Vue.js.</subheading>
    </hero>
    <writing>
      <p>
        If you're seeing this, <strong>you've successfully setup a Vuestratum project!</strong> 🔥
      </p>
      <section>
        <h3>Where to from here? 🤔</h3>
        <p>Now that you've <em>technically</em> created a Vuestratum project,
        there are a few tweaks you can do to make this project yours. 😊</p>
        <ul>
          <li>
            <strong>Change the product name.</strong> Plaster your name over
            <snippet>package.json</snippet>, <snippet>public/index.html</snippet>,
            <snippet>public/manifest.json</snippet>,
            and <snippet>src/views/Index.vue</snippet>. 💁‍♀️
          </li>
          <li>
            <strong>Update the styling.</strong> Vuestratum uses variables to help
            make style modification simpler; check out the Sass files in the
            <snippet>src/assets/scss</snippet> directory. 👩‍🎨
          </li>
        </ul>
      </section>
    </writing>
  </div>
</template>

<script>
import Masthead from '@/components/headings/Masthead.vue';
import Subheading from '@/components/headings/Subheading.vue';
import Hero from '@/components/layout/Hero.vue';
import Banner from '@/components/layout/Banner.vue';
import TextSubmitInputs from '@/components/layout/TextSubmitInputs.vue';
import Snippet from '@/components/code/Snippet.vue';
import Writing from '@/components/article/Writing.vue';
import TextInput from '@/components/input/TextInput.vue';
import SubmitInput from '@/components/input/SubmitInput.vue';

export default {
  name: 'index',
  components: {
    Masthead,
    Subheading,
    Hero,
    Banner,
    TextSubmitInputs,
    Snippet,
    Writing,
    TextInput,
    SubmitInput,
  },
};
</script>

<style lang="scss" scoped>
</style>
