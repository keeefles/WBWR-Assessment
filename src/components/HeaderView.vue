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
    background-color: rgb(246, 246, 246);
    width: 1920px;
    height: 70px;
}
@media (max-width: 394px) {
    .headerBlock {
        width: 393px;
        height: 50px;
    }
}
</style>