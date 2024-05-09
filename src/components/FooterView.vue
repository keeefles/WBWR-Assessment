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
        background-color: rgb(218, 218, 218);
        width: 100%;
        height: 170px;
        margin-top: 110px;
    }
@media (max-width: 394px) {
    .footerBlock {
        width: 393px;
        height: 90px;
        margin-top: 233px; 
    }
}
@media (min-width: 1919px) {
    .footerBlock {
        margin-top: 340px;
    }
}
</style>