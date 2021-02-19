<template>
  <Container class="home">
    <Header />
    <Hero />
    <Services />
  </Container>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { Container } from "@/components/bosons";
import { Header, Hero, Services } from "@/components/organisms";

export default defineComponent({
  components: { Container, Header, Hero, Services }
});
</script>

<style lang="scss" scoped>
.home {
  display: grid;
  grid-gap: 5rem;
  margin: 5rem auto;
}
</style>
