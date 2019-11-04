<template>
  <div class="Section">
    <h2 class="Section__title">{{ title }}</h2>
    <div class="Section__content">
      <slot></slot>
    </div>
  </div>
</template>

<script>
export default {
  props: ['title']
}
</script>

<style>
.Section {
  position: relative;
}
.Section__title {
  position: sticky;
  top: 0;
  padding-top: 4rem;
  padding-bottom: 0.5rem;
  background-color: white;
}
</style>
