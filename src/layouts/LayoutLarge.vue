<script setup>
  import LargeHeader from '@/components/templates/large/LargeHeader.vue';
  import LargeAside from '@/components/templates/large/LargeAside.vue';
  import LargeFooter from '@/components/templates/large/LargeFooter.vue';
</script>
<template>
  <div id="layout-large">
    <header>
      <LargeHeader />
    </header>
    <aside>
      <LargeAside />
    </aside>
    <main>
      <RouterView />
    </main>
    <footer>
      <LargeFooter />
    </footer>
  </div>
</template>