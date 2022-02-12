<script>
import { defineComponent } from "vue";
import TestPackage3 from "@/test-package-3.vue";

export default defineComponent({
    name: "ServeDev",
    components: {
        TestPackage3,
    },
});
</script>

<template>
    <div id="app">
        <test-package-3 />
    </div>
</template>
