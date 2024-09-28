<script setup>
defineProps({
    buttonText: {
        type: String,
    }
})
</script>

<template>
    <button>{{ buttonText }}</button>
</template>