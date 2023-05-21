<script setup lang="ts">
import { useBackground } from "../hooks/useBackground"

const props = defineProps<{ image: string; class?: string }>()
const { imageStyle } = useBackground(props.image)
</script>

<template>
  <div class="grid grid-cols-2 w-full h-full">
    <div :style="imageStyle"></div>
    <div class="slidev-layout" :class="props.class">
      <slot />
    </div>
  </div>
</template>
