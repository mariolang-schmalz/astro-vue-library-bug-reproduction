<script lang="ts" setup>
defineProps<{ link?: boolean }>();
</script>

<template>
    <button class="button">
        <slot />
    </button>
</template>
