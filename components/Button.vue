<template>
    <button :style="{backgroundColor: color}"><slot/></button>
</template>

<script setup lang="ts">
const props = defineProps({
    color:{
        type: String,
        required: false,
        default: '#2fa'
    }
})
</script>

<style scoped>

</style>