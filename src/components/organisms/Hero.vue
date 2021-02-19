<template>
  <div class="hero">
    <Networks />
    <img
      src="@/assets/images/presentation.svg"
      alt="Apresentação"
      class="image"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { Networks } from "@/components/molecules";

export default defineComponent({
  components: { Networks }
});
</script>

<style lang="scss" scoped>
.hero {
  position: relative;
  display: grid;
  justify-content: center;

  .image {
    width: 80%;
    justify-self: center;
  }

  .networks {
    position: absolute;
    left: 0;
    top: 50%;
    transform: translateY(-50%);
  }
}
</style>
