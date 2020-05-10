<script>
export default {
  name: 'Started-blog'
}
</script>

<template>
  <!--START GET STARTED-->
  <section class="section section-lg bg-get-start" :style="{'background': 'url(' + require('@/assets/images/img-2.jpg') + ')'}">
    <div class="bg-overlay"></div>
    <div class="container">
      <div class="row">
        <div class="col-lg-8 offset-lg-2 text-center">
          <h1 class="get-started-title text-white">You want to be a part of our Family? </h1>
          <div class="section-title-border margin-t-20 bg-white"></div>
          <p
            class="section-subtitle font-secondary text-white text-center padding-t-30"
          >Join TRC on our Whatsapp and Social media Platform today.</p>
          <a href="#" class="btn btn-bg-white margin-t-20">
            Join Now
            <i class="mdi mdi-arrow-right"></i>
          </a>
        </div>
      </div>
    </div>
  </section>
  <!--END GET STARTED-->
</template>