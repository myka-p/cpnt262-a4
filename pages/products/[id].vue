<template>
  <div>
    <p>Product details for {{ id }}</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum aspernatur, a provident, rerum consequatur in quod vero voluptate unde ratione error temporibus, tempora maxime asperiores. Consequuntur facilis aliquam quia consequatur.</p>
  </div>
</template>

<script setup>
  const { id } = useRoute().params

  definePageMeta({
    layout: 'products'
  })
</script>

<style scoped>

</style>