<template>
  <div class="dashboard-container">
    <panel-group></panel-group>
  </div>
</template>

<script>
import PanelGroup from './components/PanelGroup'

export default {
  name: 'dashboard',
  components: {
    PanelGroup
  }
}
</script>

<style rel="stylesheet/scss" lang="scss" scoped>
.dashboard {
  &-container {
    padding: 32px;
    background-color: rgb(240, 242, 245);
    min-height: calc(100vh - 84px);
  }
}
</style>
