<script>
/**
 * Blog component
 */
export default {
  name: 'Blog'
}
</script>

<template>
  <!-- START BLOG -->
  <section class="section bg-light" id="blog">
    <div class="container">
      <div class="row">
        <div class="col-lg-8 offset-lg-2">
          <h1 class="section-title text-center">TRC Events And Programmes</h1>
          <div class="section-title-border margin-t-20"></div>
          <p
            class="section-subtitle text-muted text-center font-secondary padding-t-30"
          >TRC Programmes and Events</p>
        </div>
      </div>

      <div class="row margin-t-30">
        <div class="col-lg-4">
          <div class="blog-box margin-t-30">
            <img src="@/assets/images/blog/img-1.jpg" class="img-fluid rounded" alt />
            <div>
              <h5 class="mt-4 text-muted">Youth Week 2019</h5>
              <h4 class="mt-3">
                <a href class="blog-title">Unlocking Potentials</a>
              </h4>
              <p
                class="text-muted"
              >Unlocking Potentials was a Blessed and impactful event</p>
              <div class="mt-3">
                <a href class="read-btn">
                  Read More
                  <i class="mdi mdi-arrow-right"></i>
                </a>
              </div>
            </div>
          </div>
        </div>

        <div class="col-lg-4">
          <div class="blog-box margin-t-30">
            <img src="@/assets/images/blog/img-2.jpg" class="img-fluid rounded" alt />
            <div>
              <h5 class="mt-4 text-muted">Unlocking Potentials </h5>
              <h4 class="mt-3">
                <a href class="blog-title">New exhibition at our Museum</a>
              </h4>
              <p
                class="text-muted"
              >Unlocking Potentials was a Blessed and impactful event....</p>
              <div class="mt-3">
                <a href class="read-btn">
                  Read More
                  <i class="mdi mdi-arrow-right"></i>
                </a>
              </div>
            </div>
          </div>
        </div>

        <div class="col-lg-4">
          <div class="blog-box margin-t-30">
            <img src="@/assets/images/blog/img-3.jpg" class="img-fluid rounded" alt />
            <div>
              <h5 class="mt-4 text-muted">TRC Women Summit</h5>
              <h4 class="mt-3">
                <a href class="blog-title">Why are so many people..</a>
              </h4>
              <p
                class="text-muted"
              >Youthweek jnckdwqc;lkwemfckm m;llmcwqlmcq</p>
              <div class="mt-3">
                <a href class="read-btn">
                  Read More
                  <i class="mdi mdi-arrow-right"></i>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- END BLOG -->
</template>