<template>
  <h1>{{ msg }}</h1>
  <Content/>
</template>

<script>
import { ref } from 'vue';

export default {
  setup() {
    const msg =  ref('this is custom layout');

    return { msg }
  }
}
</script>