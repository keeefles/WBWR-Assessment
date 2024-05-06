<template>
    <div class="headerBlock">
        <p>This is the header text. It is not supposed to show but the block shall be visible.</p>
    </div>
</template>

<script>
    export default {
       name: 'HeaderView', 
    }
</script>

<style scoped>
.headerBlock {
    background-color: rgb(235, 235, 235);
    width: 100vw;
    height: 80px;
}
</style>