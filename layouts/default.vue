<template>
  <div class='d-flex flex-column main-container'>
    <div class='d-flex'>
      <section-header />
    </div>
    <div class='d-flex flex-grow-1'>
      <section-sidebar />
      <Nuxt />
    </div>
  </div>
</template>

<script>
import SectionHeader from '../components/theme/section-header'
import SectionSidebar from '../components/theme/section-sidebar'

export default {
  components: { SectionSidebar, SectionHeader },
  data() {
    return {}
  }
}
</script>
