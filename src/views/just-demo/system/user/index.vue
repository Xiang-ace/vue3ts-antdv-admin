<template>
  <SplitPanel>
    <template #left-content>
      <DeptTree />
    </template>
    <template #right-content>
      <div>right</div>
    </template>
  </SplitPanel>
</template>

<script setup name="" lang="ts">
  import DeptTree from './components/DeptTree.vue';
</script>

<style lang="scss" scoped></style>
