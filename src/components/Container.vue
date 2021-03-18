<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class Container extends Vue {
  @Prop(Boolean) private fluid!: boolean;
}
</script>

<template>
  <selection :class="['container', { fluid: fluid }]">
    <slot />
  </selection>
</template>

<style scoped>

</style>
