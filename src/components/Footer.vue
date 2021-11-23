<script setup lang="ts">
  const date = `${new Date().getFullYear()}`
</script>

<template>
  <div class="h-16 flex py-4 px-4 w-full mb-6 md:mb-0">
    <p class="mx-auto" style="color: #e8e8b7">
      © <a href="/" class="text-purple-500">Rizoto bar</a> {{ date }}, All
      rights Reserved
    </p>
  </div>
</template>
