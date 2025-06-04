<template>
  <div class="about-area about-2 fix">
    <div class="container-full">
      <div class="row">
        <div class="col-md-5 col-sm-4 col-xs-12">
          <div class="about-image">
            <div class="video-content ">
              <a href="https://www.youtube.com/watch?v=YgQR_zbdLDw" class="video-play vid-zone">
                <i class="fa fa-play"></i>
              </a>
            </div>
          </div>
        </div>
        <div class="col-md-7 col-sm-8 col-xs-12">
          <div class="support-all about-content">
            <div class="section-headline right-headline white-headline">
              <h3>Health <span class="color">Experts You Can</span> Trust for Every Stage of Life</h3>
              <p>At Dr. Nuredin Luke Medium Clinic, we provide professional, evidence-based care with a deep commitment to the well-being of our community. From maternal care to chronic disease management, our team ensures you receive timely, respectful, and expert treatment.</p>
            </div>
            <div class="about-company">
              <div class="single-about">
                <span class="about-text">24/7 Medical Service</span>
                <span class="about-text">Maternal Health</span>
                <span class="about-text">Diabetes & Heart Check</span>
                <span class="about-text">Modern Lab</span>
              </div>
              <div class="single-about">
                <span class="about-text">HIV & TB Screening</span>
                <span class="about-text">Compassionate Staff</span>
                <span class="about-text">Trusted Across Oromia</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
    export default {
        name: "About",
      mounted() {
        $('.video-play').magnificPopup({
          type: 'iframe'
        });
      }
    }
</script>

<style scoped>

</style>
