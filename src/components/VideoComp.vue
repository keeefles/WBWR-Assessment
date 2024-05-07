<template>
    <div>
        <video src="@/assets/videos/UA_Theme_1_DT.mp4" loop autoplay width="1920px"></video>

        <div class="video-text">
            <div class="heading1">
               <h1 class="idk">{{ videoText }}</h1> 
            </div>
            <p class="p-text">{{ paragraphText }}</p><br>
      <div class="bottun">
        <button class="button">Shop UA New Arrivals</button>
      </div>
        </div>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                videoText: 'CHECK OUT OUR LATEST GEAR',
                paragraphText: 'Advanced tech, superior comfort and all performance is what our latest UA gear is all about. Built to go further, push hard and break your boundaries.',
            }
        }
    }
</script>

<style scoped>
.idk {
    position: absolute;
    top: 25%;
    left: 73%;
    width: 300px;
    font-size: 105px;
    color: black;
    font-family: "Neue Plak Condensed Black", sans-serif;
    line-height: 0.8;
}

.p-text {
    position: absolute;
    top: 77%;
    left: 69%;
    font-family: 'Neue Plak Regular';
    font-size: 12px;
}

.button {
    position: absolute;
    top: 90%;
    left: 73%;
    font-family: 'Neue Plak Regular';
    font-size: 14px;
}
</style>