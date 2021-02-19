<template>
  <nav class="navbar">
    <Link to="/services" text="Serviços" />
    <Link to="/about" text="Sobre mim" />
    <Link to="/cases" text="Casos" />
    <Link to="/contact" text="Contanto" />
  </nav>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { Link } from "@/components/atoms";

export default defineComponent({
  components: { Link }
});
</script>

<style lang="scss" scoped>
.navbar {
  display: grid;
  grid-gap: 2rem;
  width: max-content;
  grid-auto-flow: column;
}
</style>
