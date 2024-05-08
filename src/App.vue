<template>
  <HeaderView/>
  <VideoComp/>
  <HomeView/>
  <FooterView/>
</template>

<script>
import FooterView from '@/components/FooterView.vue';
import HeaderView from '@/components/HeaderView.vue';
import HomeView from '@/views/HomeView.vue';
import VideoComp from '@/components/VideoComp.vue';

export default {
  components: {
    HeaderView,
    FooterView,
    HomeView,
    VideoComp,
  },
}
</script>

<style>

</style>
