<script setup>
defineProps({
    buttonText: {
        type: String,
        default: "Button Default"
    }
})
</script>

<template>
    <button>{{ buttonText }}</button>
</template>