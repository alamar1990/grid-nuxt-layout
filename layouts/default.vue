<template>
  <div class='d-flex flex-column main-container'>
    <div class='d-flex'>
      <section-header />
    </div>
    <div class='d-flex flex-row flex-grow-1'>
      <section-sidebar />
      <section-main />
    </div>
  </div>
</template>

<script>
import SectionHeader from '../components/theme/section-header'
import SectionSidebar from '../components/theme/section-sidebar'
import SectionMain from '../components/theme/section-main'

export default {
  components: { SectionMain, SectionSidebar, SectionHeader },
  data() {
    return {}
  }
}
</script>
