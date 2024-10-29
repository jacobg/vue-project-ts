<script>
import { markRaw, toRaw } from 'vue'

export default {
  data() {
    return {
      value1: markRaw({}),
      value2: toRaw({}),
    }
  },
}
</script>

<template>
  <div>
    <div>Value 1 = {{ value1 }}</div>
    <div>Value 2 = {{ value2 }}</div>
  </div>
</template>
