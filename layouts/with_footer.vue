<template>
  <div class="page-wrapper">
    <Header />
    <main class="content">
      <NuxtPage />
    </main>
    <Footer v-if="hasFooter" />
  </div>
</template>

<script setup>
import Header from '~/components/Header.vue'
import Footer from '~/components/Footer.vue'

const hasFooter = true // This layout shows the footer.
</script>

<style scoped>
.page-wrapper {
  min-height: 100vh; /* full height */
  display: flex;
  flex-direction: column;
}

.content {
  flex: 1; /* take all space between header and footer */
}
</style>
