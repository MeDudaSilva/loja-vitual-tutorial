<script setup>
  import MediumHeader from '@/components/templates/medium/MediumHeader.vue';
  import MediumAside from '@/components/templates/medium/MediumAside.vue';
  import MediumFooter from '@/components/templates/medium/MediumFooter.vue';
import { RouterView } from 'vue-router';
</script>

<template>
  <div id="layout-medium">
    <header>
      <MediumHeader />
    </header>
    <aside>
      <MediumAside />
    </aside>
    <main>
      <RouterView />
    </main>
    <footer>
      <MediumFooter />
    </footer>
  </div>
</template>