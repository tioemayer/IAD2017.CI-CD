<template>
  <div class="container">
    <Section title="Text">
      <img src="~/assets/img/gbgr_01_0418.jpg" />
      <Blindtext size="3" />
    </Section>
    <Section title="Fähigkeit">
      <Skill title="Design" level="90" />
      <Skill title="Code" level="50" />
      <Skill title="Management" level="70" />
    </Section>

    <Section title="Text">
      <Blindtext size="3" />
    </Section>
  </div>
</template>

<script>
import Skill from '~/components/Skill.vue'
import Section from '~/components/Section.vue'
import Blindtext from '~/components/Blindtext.vue'

export default {
  components: {
    Skill,
    Section,
    Blindtext
  }
}
</script>

<style>
.container {
  width: 96%;
  margin: 0 auto;
  max-width: 40em;
}
</style>
