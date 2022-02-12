<script>
import { defineComponent } from 'vue';
import TestPackage-3 from '@/test-package-3.vue';

export default defineComponent({
  name: 'ServeDev',
  components: {
    TestPackage-3
  }
});
</script>

<template>
  <div id="app">
    <test-package-3 />
  </div>
</template>
