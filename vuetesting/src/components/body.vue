<template>
    <div class="body-grid">
        <div></div>
        <h2>Side-Panel</h2>
        <h2>Meet the Dev</h2>
        <h2>Meet the Team</h2>
    </div>
</template>


<script>
    export default {
        name: "page-body"
    }
</script>


<style scoped>
    .body-grid {
        display: grid;
        justify-items: center;
        align-items: center;
        grid-template-columns: 1fr 2fr 1fr 1fr 1fr;
    }
    
</style>