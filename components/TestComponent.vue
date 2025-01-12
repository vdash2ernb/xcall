<template>
    <div>
        <span class=" text-green-500">Hello ernest123</span>

        <button @click="clickedBtn" class="btn btn-primary btn-sm">click me</button>
    </div>
</template>

<script setup lang="ts">
    const clickedBtn = ()=> {
        alert('hello world')
    }
</script>

<style scoped>

</style>