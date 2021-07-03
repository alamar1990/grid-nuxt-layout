<template>
  <div>
    <div class='container'>
      <section-header></section-header>
      <section-sidebar></section-sidebar>
      <div class='section-main'>
        <Nuxt />
      </div>
    </div>
  </div>
</template>

<script>
import SectionHeader from '~/components/layout_components/section-header'
import SectionSidebar from '~/components/layout_components/section-sidebar'

export default {
  components: { SectionSidebar, SectionHeader }
}
</script>

<style scoped>

</style>
