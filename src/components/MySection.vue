<template>
  <div class="MySection">
    <fieldset>
      <legend>{{title}}</legend>
      <slot></slot>
    </fieldset>
  </div>
</template>

<script>
export default {
  name: 'MySection',
  props: {
    title: String
  }
}
</script>

<style scoped>
.MySection {
  display:inline-block;
}
.MySection fieldset {
  border-radius: 50px;
  border-color: #e1e1e1; 
}
.MySection legend {
  font-weight:bold;
}
</style>
