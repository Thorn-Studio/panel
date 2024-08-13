<template>
    <div>
        <h1>Showing Server UUID: {{ uuid }}</h1>
    </div>
</template>

<script setup>
const { uuid } = useRoute().params;
definePageMeta({
    layout: "server",
});
</script>

<style scoped></style>
