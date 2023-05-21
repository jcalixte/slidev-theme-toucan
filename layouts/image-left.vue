<script setup lang="ts">
import { useBackground } from "../hooks/useBackground"

const props = defineProps<{ image: string }>()
const { imageStyle } = useBackground(props.image)
</script>

<template>
  <div class="grid grid-cols-2 w-full h-full">
    <div :style="imageStyle"></div>
    <div class="slidev-layout">
      <slot />
    </div>
  </div>
</template>
