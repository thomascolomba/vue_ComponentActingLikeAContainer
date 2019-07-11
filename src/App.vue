<template>
  <div id="app">
    <MySection title="My very titly title">
      <div>My beautiful section content</div>
      <div>A long useless sentence to fill the content.</div>
      <div>What a beautiful content</div>
    </MySection>
  </div>
</template>

<script>
import MySection from './components/MySection.vue'

export default {
  name: 'app',
  components: {
    MySection
  }
}
</script>

<style>
#app {
  text-align:center;
}
</style>
