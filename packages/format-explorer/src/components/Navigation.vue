<script setup lang="ts">
const commitURL = `https://github.com/intlify/vue-i18n-next/tree/${__COMMIT__}`
const commitLabel = `@${__COMMIT__}`
const commitHistoryURL = 'https://app.netlify.com/sites/format-explorer/deploys'
</script>

<template>
  <h2>Intlify Message Format Explorer</h2>
  <!-- eslint-disable-next-line vue/no-multiple-template-root -->
  <a :href="commitURL" target="_blank">{{ commitLabel }}</a>
  |
  <a :href="commitHistoryURL" target="_blank">History</a>
</template>

<style scoped>
h2 {
  margin: 0;
  margin-left: 2rem;
  margin-right: 2rem;
  display: inline-block;
}
ul {
  list-style-type: none;
  display: inline-block;
}
a {
  font-weight: 600;
  color: #ffad33;
}
</style>
