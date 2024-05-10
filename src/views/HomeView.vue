<template>
  <!-- start of categories -->
  <section class="sec1">
    <h2 class="gear-bear">Our best gear</h2>
    <p class="gb-unlock">Unlock your potential with the best UA Gear.</p>
    <!-- start of carousel -->
    <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://iili.io/JrRvbRe.md.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://iili.io/JrR8AgI.md.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://iili.io/JrR8BOg.md.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://iili.io/JrR80Xf.md.jpg" class="d-block w-100" alt="...">
    </div>
  </div>
</div>
      <!-- end of carousel  -->
    <!-- images inserted -->
    <div class="gear-images">
      <div class="gb-img">
        <img src="https://iili.io/JrRvbRe.md.jpg" class="gb-img" alt="Train" />
        <div class="disappearo">Shop Now</div>
      </div>
      <div class="gb-img">
        <img src="https://iili.io/JrR8AgI.md.jpg" class="gb-img" alt="Run" />
        <div class="disappearo">Shop Now</div>
      </div>
      <div class="gb-img">
        <img src="https://iili.io/JrR8BOg.md.jpg" class="gb-img" alt="Golf" />
        <div class="disappearo">Shop Now</div>
      </div>
      <div class="gb-img">
        <img
          src="https://iili.io/JrR80Xf.md.jpg"
          class="gb-img"
          alt="Accessories"
        />
        <div class="disappearo">Shop Now</div>
      </div>
    </div>
    <br />
  </section>
  <!-- end of categories -->
  <!-- start of Project Rock -->
  <section class="sec2">
    <div class="project-rockInfo">
      <div class="project-rock">
        <img
          src="@\assets\photos\UA_Theme_2_DT.jpg"
          width="1500px"
          class="desktop ua-theme"
          alt="Project Rock img"
        />
        <img
          src="@\assets\photos\UA_Theme_2_MB.jpg"
          width="393px"
          class="mobile"
          alt="Project Rock img"
        />
      </div>
      <div>
        <h2 class="pr-name">Project Rock</h2>
        <br />
        <h2 class="bold-text">EVERY SIDE OF STRONG</h2>
        <br />
        <p class="pr-text">
          The Underground collection is inspired by the idea of a Project Rock
          fight club. A place where we push each other harder to make each toher
          stronger. A drop dedicated to you and your crew. The neon colourways
          are a reflection of the energy we bring to every rep, every set and
          every challenge.
        </p>
        <br />
        <button class="buttons">Shop Project Rock</button>
      </div>
    </div>
  </section>
  <!-- end of project rock -->
  <!-- start of promotions -->
  <section class="sec3">
    <div class="promo">
      <h2 class="gear-bear">Discover out lastest promotions</h2>
      <p>Get the best deals on our best gear.</p>
      <!-- start of carousel -->
      <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://iili.io/JrR8LhJ.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://iili.io/JrRSETg.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://iili.io/JrRS9kX.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://iili.io/JrRSfEl.jpg" class="d-block w-100" alt="...">
    </div>
  </div>
</div>
      <!-- end of carousel -->
      <div class="promo-img">
        <img
          src="https://iili.io/JrR8LhJ.jpg"
          id="promo"
          alt="buy 2 for R700"
        />
        <img
          src="https://iili.io/JrRSETg.jpg"
          id="promo"
          alt="buy 2 for R800"
        />
        <img
          src="https://iili.io/JrRS9kX.jpg"
          id="promo"
          alt="buy 2 for R1000"
        />
        <img
          src="https://iili.io/JrRSfEl.jpg"
          id="promo"
          alt="buy 2 for R1200"
        />
      </div>
    </div>
  </section>
  <!-- end of promo -->
  <!-- start of insta -->
  <section class="sec3" >
    <div class="insta">
      <h2 class="gear-bear">What's happening on Instagram</h2>
      <p class="gb-text">
        Don't miss out on the latest news and updates from Under Armour.
      </p>
      <br />
      <div class="row">
        <div class="video" id="video">
          <video
            src="@/assets/videos/ig_video.mp4"
            class="vio"
            loop
            autoplay
            muted
          ></video>
        </div>
        <div class="images">
          <img
            class="img1"
            src="https://iili.io/JrRUSHP.md.jpg"
            alt="dwayne wearing a project rock jacket"
          />
          <img
            class="img2"
            src="https://iili.io/JrRgfJS.md.jpg"
            alt="random light skinned guy"
          />
          <div class="images">
            <img
              class="img3"
              src="https://iili.io/JrRgxWb.md.jpg"
              alt="girl running for the gram"
            />
            <img
              class="img4"
              src="https://iili.io/JrRgAgV.md.jpg"
              alt="the rock lifting his body weight"
            />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "HomeView",
}
</script>

<style src="@/assets/style/style.css"></style>
