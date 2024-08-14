<template>
  <div id="app">
    <hello-world />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { MakunouchiToolsSample } from '@/entry.esm';

export default defineComponent({
  name: 'ServeDev',
  // components: {
  //  MakunouchiToolsSample,
  // }
});
</script>
