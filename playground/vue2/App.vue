<template>
  <h1 id="title">{{ message }}</h1>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'App',
  data() {
    return {
      message: 'hello world'
    }
  },
})
</script>

<style scoped>

</style>
