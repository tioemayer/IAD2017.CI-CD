<template>
  <div class="Skill">
    <h3 class="Skill__title">{{ title }}</h3>
    <div class="Skill__background">
      <div class="Skill__level" :style="{ width: level + '%' }">
        <span class="Skill__number">{{ level }}%</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ['title', 'level']
}
</script>

<style>
.Skill__title {
  padding-top: 1rem;
  padding-bottom: 0.5rem;
}

.Skill__background {
  background-color: #cccccc;
}
.Skill__level {
  background-color: #5f7b9c;
}
.Skill__number {
  padding: 0.3rem 0.5rem;
  display: inline-block;
  color: white;
}
</style>
