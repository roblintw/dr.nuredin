<template>
  <div class="quote-area bg-color area-padding">
    <div class="container ">
      <div class="row">
        <div class="col-md-12 col-sm-12 ">
          <div class="row ">
            <div class="col-md-5 col-sm-4 col-xs-12">
              <div class="sub-head white-headline">
                <h3>Need Help or More Information?  <span class="color">Let Us Contact You.</span></h3>
                <p>Fill out the form and our clinic staff will call you back as soon as possible. We’re happy to answer your questions or help you book an appointment.</p>
              </div>
            </div>
            <div class="col-md-7 col-sm-8 col-xs-12">
              <div class="row">
                <form id="contactForm" method="POST" action="#" class="contact-form">
                  <div class="col-md-6 col-sm-6 col-xs-12">
                    <input type="text" id="name" class="form-control" placeholder="Name" required data-error="Please enter your name">
                    <div class="help-block with-errors"></div>
                    <input type="email" class="email form-control" id="email" placeholder="Email" required data-error="Please enter your email">
                    <div class="help-block with-errors"></div>
                    <input type="text" id="msg_Reason" class="form-control last-part" placeholder="Reason" required data-error="Please enter your message subject">
                    <div class="help-block with-errors last-part"></div>
                  </div>
                  <div class="col-md-6 col-sm-6 col-xs-12">
                    <textarea id="message" rows="7" placeholder="Message" class="form-control" required data-error="Write your message"></textarea>
                    <div class="help-block with-errors"></div>
                    <button type="submit" id="submit" class="quote-btn">Submit</button>
                    <div id="msgSubmit" class="h3 text-center hidden"></div>
                    <div class="clearfix"></div>
                  </div>
                </form>
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
        name: "Quote"
    }
</script>

<style scoped>

</style>
