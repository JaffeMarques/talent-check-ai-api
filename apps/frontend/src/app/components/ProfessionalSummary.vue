<template>
  <section class="mb-6">
    <h2 class="text-2xl font-semibold mb-3 text-purple-500">Professional Summary</h2>
    <ul class="list-disc list-inside space-y-2">
      <li v-for="(item, index) in summary" :key="index">
        {{ item }}
      </li>
    </ul>
  </section>
</template>

<script>
export default {
  name: 'ProfessionalSummary',
  props: {
    summary: Array,
  },
};
</script>