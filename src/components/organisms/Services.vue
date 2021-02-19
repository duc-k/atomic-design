<template>
  <section class="services">
    <Service
      title="Front End"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae error praesentium totam. Natus nam cupiditate, blanditiis molestias fugiat perspiciatis cumque consequatur doloremque ea unde eos veniam provident reprehenderit quod dicta."
    />
    <Service
      title="Back End"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae error praesentium totam. Natus nam cupiditate, blanditiis molestias fugiat perspiciatis cumque consequatur doloremque ea unde eos veniam provident reprehenderit quod dicta."
    />
    <Service
      title="Manutenção"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae error praesentium totam. Natus nam cupiditate, blanditiis molestias fugiat perspiciatis cumque consequatur doloremque ea unde eos veniam provident reprehenderit quod dicta."
    />
  </section>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { Service } from "@/components/molecules";

export default defineComponent({
  components: { Service }
});
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-gap: 5rem;
  grid-template-columns: repeat(3, 1fr);
}
</style>
