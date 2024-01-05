<script setup lang="ts">
import DashboardBubble from './DashboardBubble.vue'
</script>

<template>
    <div class="dashboard-container">
        <h1>
            <slot name="bob">Dashboard thingy</slot>
        </h1>
    </div>
</template>
  
<style scoped>
.dashboard-container {
    background-color: aquamarine;
    border-radius: 10px;
}
.dashboard-container h1 {
    color: #111;
}
</style>