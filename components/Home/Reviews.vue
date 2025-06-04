<template>
  <div class="reviews-area area-padding">
    <div class="container">
      <div class="row">
        <div class="col-md-12 col-sm-12 col-xs-12">
          <div class="section-headline text-center">
            <h3>What Our Patients Say</h3>
            <p>Real feedback from patients who received care at Dr. Nuredin Luke Medium Clinic. We are honored to serve with compassion, professionalism, and trust.</p>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-12 col-sm-12 col-xs-12">
          <div class="Reviews-content">
            <div class="testimonial-carousel item-indicator">
              <div class="single-testi">
                <div class="testi-text">
                  <div class="clients-text">
                    <div class="client-rating">
                      <a href="#"><i class="ti-star"></i></a>
                      <a href="#"><i class="ti-star"></i></a>
                      <a href="#"><i class="ti-star"></i></a>
                      <a href="#"><i class="ti-star"></i></a>
                      <a href="#"><i class="ti-star"></i></a>
                    </div>
                    <p>I had a safe delivery thanks to the amazing staff at Dr. Nuredin’s clinic. The care and comfort I received were beyond my expectations.</p>
                    <div class="testi-img ">
                      <div class="guest-details">
                        <h4>Selam Abebe</h4>
                        <span class="guest-rev">Maternity Care Patient</span>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="single-testi">
                <div class="testi-text">
                  <div class="clients-text">
                    <div class="client-rating">
                      <a href="#"><i class="ti-star"></i></a>
                      <a href="#"><i class="ti-star"></i></a>
                      <a href="#"><i class="ti-star"></i></a>
                      <a href="#"><i class="ti-star"></i></a>
                      <a href="#"><i class="ti-star"></i></a>
                    </div>
                    <p>I brought my elderly father for diabetes care. We were treated with patience and professionalism. The lab services were fast and accurate.</p>
                    <div class="testi-img ">
                      <div class="guest-details">
                        <h4>Kedir Ahmed</h4>
                        <span class="guest-rev">Diabetes Patient</span>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="single-testi">
                <div class="testi-text">
                  <div class="clients-text">
                    <div class="client-rating">
                      <a href="#"><i class="ti-star"></i></a>
                      <a href="#"><i class="ti-star"></i></a>
                      <a href="#"><i class="ti-star"></i></a>
                      <a href="#"><i class="ti-star"></i></a>
                      <a href="#"><i class="ti-star"></i></a>
                    </div>
                    <p>They helped me manage my blood pressure with expert advice and kindness. I feel stronger and more confident in my health.</p>
                    <div class="testi-img ">
                      <div class="guest-details">
                        <h4>Amina Gemeda</h4>
                        <span class="guest-rev">Patient</span>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="single-testi">
                <div class="testi-text">
                  <div class="clients-text">
                    <div class="client-rating">
                      <a href="#"><i class="ti-star"></i></a>
                      <a href="#"><i class="ti-star"></i></a>
                      <a href="#"><i class="ti-star"></i></a>
                      <a href="#"><i class="ti-star"></i></a>
                      <a href="#"><i class="ti-star"></i></a>
                    </div>
                    <p>The doctors really listen to you. They’re professional, respectful, and always ready to help. Highly recommend this clinic.</p>
                    <div class="testi-img ">
                      <div class="guest-details">
                        <h4>Biftu Tullu</h4>
                        <span class="guest-rev">Family Member</span>
                      </div>
                    </div>
                  </div>
                </div>
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
        name: "Reviews",
      mounted() {
        var review = $('.testimonial-carousel');
        review.owlCarousel({
          loop:true,
          nav:false,
          margin:15,
          center:true,
          dots:true,
          autoplay:false,
          responsive:{
            0:{
              items:1
            },
            768:{
              items:2
            },
            1000:{
              items:3
            }
          }
        });
      }
    }
</script>

<style scoped>

</style>
