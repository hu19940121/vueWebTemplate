<template>
  <div :class="classObj" class="app-wrapper">
    <Header />
    <div class="main-container">
      <app-main />
    </div>
  </div>
</template>

<script>
import { Header, AppMain } from './components'
export default {
  name: 'Layout',
  components: {
    Header,
    AppMain
  },
  computed: {
  },
  methods: {
  }
}
</script>

<style lang="less" scoped>
  .app-wrapper {
    position: relative;
    height: 100%;
    width: 100%;
  }
</style>
