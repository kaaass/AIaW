<template>
  <q-item
    clickable
    v-close-popup
    min-h-0
  >
    <q-item-section
      avatar
      min-w-0
    >
      <q-icon
        important:text="20px"
        :name="icon"
      />
    </q-item-section>
    <q-item-section>{{ label }}</q-item-section>
  </q-item>
</template>

<script setup lang="ts">
defineProps<{
  icon: string
  label: string
}>()
</script>
