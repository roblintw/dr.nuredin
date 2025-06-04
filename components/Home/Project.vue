<template>
    <div class="project-area area-padding">
        <div class="container">
            <div class="row">
                <div class="col-md-12 col-sm-12 col-xs-12">
                    <div class="section-headline text-center">
                        <h3>Our Commitment to Quality Healthcare</h3>
                        <p>
                            At Dr. Nuredin Luke Medium Clinic, we focus on compassionate care, advanced diagnostics, and trustworthy service. These are the pillars of our success.
                        </p>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="project-carousel">
                    <div class="col-md-4 col-sm-4 col-xs-12">
                        <div class="single-awesome-project">
                            <div class="awesome-img">
                                <a href="#">
                                    <img src="/img/project/p1.jpg" alt="" />
                                </a>
                                <div class="add-actions text-center">
                                    <a
                                        class="venobox"
                                        data-gall="myGallery"
                                        href="/img/project/p1.jpg"
                                    >
                                        <i class="port-icon ti-zoom-in"></i>
                                    </a>
                                </div>
                            </div>
                            <div class="project-dec">
                                <h4>Patient-Centered Care</h4>
                                <p>
                                    We prioritize the needs of every patient by offering respectful, culturally sensitive, and personalized medical support.
                                </p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 col-sm-4 col-xs-12">
                        <div class="single-awesome-project">
                            <div class="awesome-img">
                                <a href="#">
                                    <img src="/img/project/p2.jpg" alt="" />
                                </a>
                                <div class="add-actions text-center">
                                    <a
                                        class="venobox"
                                        data-gall="myGallery"
                                        href="/img/project/p2.jpg"
                                    >
                                        <i class="port-icon ti-zoom-in"></i>
                                    </a>
                                </div>
                            </div>
                            <div class="project-dec">
                                <h4>Women’s Health & Delivery</h4>
                                <p>
                                    From pregnancy monitoring to childbirth support, we provide expert care for mothers and babies with compassion and professionalism.
                                </p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 col-sm-4 col-xs-12">
                        <div class="single-awesome-project">
                            <div class="awesome-img">
                                <a href="#">
                                    <img src="/img/project/p3.jpg" alt="" />
                                </a>
                                <div class="add-actions text-center">
                                    <a
                                        class="venobox"
                                        data-gall="myGallery"
                                        href="/img/project/p3.jpg"
                                    >
                                        <i class="port-icon ti-zoom-in"></i>
                                    </a>
                                </div>
                            </div>
                            <div class="project-dec">
                                <h4>Chronic Disease Management</h4>
                                <p>
                                    Our team supports patients with diabetes, hypertension, and other chronic illnesses through early detection and long-term care plans.

                                </p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 col-sm-4 col-xs-12">
                        <!-- single-awesome-project start -->
                        <div class="single-awesome-project">
                            <div class="awesome-img">
                                <a href="#">
                                    <img src="/img/project/p4.jpg" alt="" />
                                </a>
                                <div class="add-actions text-center">
                                    <a
                                        class="venobox"
                                        data-gall="myGallery"
                                        href="/img/project/p4.jpg"
                                    >
                                        <i class="port-icon ti-zoom-in"></i>
                                    </a>
                                </div>
                            </div>
                            <div class="project-dec">
                                <h4>Modern Diagnostics</h4>
                                <p>
                                    Equipped with reliable testing and laboratory services, we ensure accurate diagnosis for effective treatment.
                                </p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 col-sm-4 col-xs-12">
                        <div class="single-awesome-project">
                            <div class="awesome-img">
                                <a href="#">
                                    <img src="/img/project/p5.jpg" alt="" />
                                </a>
                                <div class="add-actions text-center">
                                    <a
                                        class="venobox"
                                        data-gall="myGallery"
                                        href="/img/project/p5.jpg"
                                    >
                                        <i class="port-icon ti-zoom-in"></i>
                                    </a>
                                </div>
                            </div>
                            <div class="project-dec">
                                <h4>24/7 Availability</h4>
                                <p>
                                    Whether day or night, we’re available to serve our community with round-the-clock medical attention and care.
                                </p>
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
    name: "Project",
    mounted() {
        var Project_carousel = $(".project-carousel");
        Project_carousel.owlCarousel({
            loop: true,
            nav: true,
            autoplay: false,
            dots: false,
            navText: [
                "<i class='ti-angle-left'></i>",
                "<i class='ti-angle-right'></i>",
            ],
            responsive: {
                0: {
                    items: 1,
                },
                700: {
                    items: 2,
                },
                1000: {
                    items: 3,
                },
            },
        });
    },
};
</script>

<style scoped>
</style>
