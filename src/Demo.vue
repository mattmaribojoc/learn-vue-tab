<template lang="html">
  <div>
    <tabs>
      <tab title="Tab 1">Hello From Tab 1</tab>
      <tab title="Tab 2">Hello From Tab 2</tab>
      <tab title="Tab 3">Hello From Tab 3</tab>
      <tab title="Tab 4">Hello From Tab 4</tab>
    </tabs>
  </div>
</template>

<script>
import Tab from './Tab.vue'
import Tabs from './Tabs.vue'

export default {
  components: {
    Tab,
    Tabs
  }
}
</script>

<style lang="css">
</style>
