<script setup>
  import SmallHeader from '@/components/templates/small/SmallHeader.vue';
  import SmallFooter from '@/components/templates/small/SmallFooter.vue';
</script>

<template>
  <div id="layout-small">
    <header>
      <SmallHeader />
    </header>
    <main>
      <RouterView />
    </main>
    <footer>
      <SmallFooter />
    </footer>
  </div>
</template>