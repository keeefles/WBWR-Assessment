<template>
    <div class="headerBlock"></div>
</template>

<script>
    export default {
       name: 'HeaderView', 
    }
</script>

<style scoped>
.headerBlock {
    background-color: #d9d9d9;
    width: 100%;
    height: 70px;
}
@media (max-width: 394px) {
    .headerBlock {
        width: 393px;
        height: 50px;
    }
}
</style>