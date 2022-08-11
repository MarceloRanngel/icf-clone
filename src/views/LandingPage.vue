<template>
    <div>
        <NavBar></NavBar>
    </div>
</template>

<script lang="ts">

import NavBar from '@/components/NavBar.vue';

export default {
    name: 'LandingPage',
    components: { NavBar }
}
</script>

<style scoped>
.body {
    font-family: Nunito,sans-serif;
    font-size: .8rem;
    font-weight: 400;
    color: #212121;
    background: #f8f8f8;
}
</style>