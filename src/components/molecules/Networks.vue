<template>
  <div class="networks">
    <Social name="Github" to="https://github.com" icon="github.svg" />
    <Social name="Twitter" to="https://twitter.com" icon="twitter.svg" />
    <Social name="Facebook" to="https://facebook.com" icon="facebook.svg" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { Social } from "@/components/atoms";

export default defineComponent({
  components: { Social }
});
</script>

<style lang="scss" scoped>
.networks {
  display: grid;
  grid-gap: 1rem;
}
</style>
