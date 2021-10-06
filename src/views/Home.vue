<template>
  <p> hi {{name}} </p>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
 name: 'App',
 setup () {
  const name = "Jim"

  return {
    name
  }
 }
});
</script>
