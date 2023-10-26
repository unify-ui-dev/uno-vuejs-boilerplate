<template>
    <NavbarEl/>
    <slot/>
    <FooterEl/>
</template>
<script setup lang="ts">
import FooterEl from '../element/FooterEl.vue';
import NavbarEl from '../element/NavbarEl.vue';
</script>
