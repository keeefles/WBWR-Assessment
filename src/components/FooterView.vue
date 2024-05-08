<template>
    <div class="footerBlock"></div>
</template>

<script>
    export default {
        name: 'FooterView',
    }
</script>

<style scoped>
    .footerBlock {
        background-color: rgb(235, 235, 235);
        width: 1920px;
        height: 170px;
        margin-top: 15px;
    }
@media (max-width: 394px) {
    .footerBlock {
        width: 393px;
        height: 80px;
        margin-top: 252px; 
    }
}
</style>