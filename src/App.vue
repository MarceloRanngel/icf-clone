<template>
  <router-view/>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

  export default defineComponent({
    name: "App"
});
</script>

<style>
body {
    font-family: nunito,sans-serif;
    font-size: .8rem;
    font-weight: 400;
    color: #212121;
    background: #f8f8f8;
}

</style>
