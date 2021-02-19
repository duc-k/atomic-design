<template>
  <header class="header">
    <Logo />
    <Navbar />
    <Search />
  </header>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { Logo } from "@/components/atoms";
import { Navbar, Search } from "@/components/molecules";

export default defineComponent({
  components: { Logo, Navbar, Search }
});
</script>

<style lang="scss" scoped>
.header {
  width: 100%;
  display: grid;
  grid-template-columns: 160px repeat(2, auto);
  align-items: center;
  justify-content: space-between;
}
</style>
