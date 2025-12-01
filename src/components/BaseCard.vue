<template>
  <div class="base-card">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'BaseCard'
}
</script>

<style scoped>
.base-card {
  background: #011F35;
  border-radius: 16px;
  min-height: 32px;
  min-width: 32px;
}
</style>