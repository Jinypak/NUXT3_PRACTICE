<template>
  <div :class="{'dark': darkMode}">
    <div class="min-h-full">
      <div class="grid grid-cols-12 mx-auto sm:px-6 lg:max-w-7xl lg:px-8 lg:gap-5">
        <h1>아하</h1>
      </div>
    </div>
  </div>
</template>

<script setup>
const darkMode = ref(true);

</script>