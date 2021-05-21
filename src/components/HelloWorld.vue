<template>
  <h1 class="text-5xl text-blue-400">{{ msg }}</h1>
</template>

<script lang="ts">
import { ref, defineComponent } from 'vue'
export default defineComponent({
  name: 'HelloWorld',
  props: {
    msg: {
      type: String,
      required: true
    }
  }
})
</script>

<style scoped>

</style>
