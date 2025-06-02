<template>
  <a-button>Add</a-button>
</template>

<script>
import { defineComponent } from "vue";
import { Button } from "ant-design-vue";

export default defineComponent({
  setup() {
    return {
      // Composition API로 필요한 것 반환
    };
  },
  components: {
    AButton: Button,
  },
});
</script>
