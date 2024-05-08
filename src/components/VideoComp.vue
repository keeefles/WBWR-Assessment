<template>
    <section>
    <div>
        <video class="desktop" src="@/assets/videos/UA_Theme_1_DT.mp4" loop autoplay width="1920px"></video>
        <video class="mobile" src="@/assets/videos/UA_Theme_1_MB.mp4" loop autoplay width="1920px"></video>

        <div class="video-text">
            <div class="heading1">
               <h1 class="idk">{{ videoText }}</h1> 
            </div>
            <p class="p-text">{{ paragraphText }}</p>
      <div class="bottun">
        <button class="button">Shop UA New Arrivals</button>
      </div>
        </div>
    </div>
    </section>
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
    font-family: "Neue Plak Condensed Black";
    line-height: 0.8;
}
.p-text {
    position: absolute;
    top: 77%;
    left: 69%;
    font-family: 'Neue Plak Regular';
    font-size: 14px;
}

.button {
    position: absolute;
    top: 90%;
    left: 73%;
    font-family: 'Neue Plak Regular';
    font-size: 14px;
}
@media (max-width: 395px) {
    .desktop {
        display: none;
    }
    .mobile {
        width: 393px;
    }
    .idk {
        font-size: 48px;
        position: static;
        width: 250px;
        margin: 10px;
    }
    .p-text {
        position: static;
        margin: 20px 10px;
        width: 345px
    }
    .button {
        position: static;
        margin: 0 10px 0 10px;
        width: 365px;
    }
    button {
        margin: 40px;
    }
}
@media (min-width: 1919px) {
    .idk {
        top: 13%;
        left: 58%;
    }
    .p-text {
        position: absolute;
        top: 48%;
        left: 55%;
    }
    .button {
        top: 58%;
        left: 58.2%;
        margin: 0;
    }
}
</style>