<template>
  <section class="container">
    <HeaderBar />
    <GuidHero />
  </section>
</template>

<<script>
import HeaderBar from '~components/Header.vue'
import GuidHero from '~components/guid-hero.vue'

export default {
  components: {
    HeaderBar,
    GuidHero
  }
}
</script>
