<script>
export default {
  name: 'Services'
}
</script>

<template>
  <div>
    <!--START SERVICES-->
    <section class="section bg-light" id="services">
      <div class="container">
        <div class="row">
          <div class="col-lg-8 offset-lg-2">
            <h1 class="section-title text-center">Our Services</h1>
            <div class="section-title-border margin-t-20"></div>
            <p
              class="section-subtitle text-muted text-center padding-t-30 font-secondary"
            >RCCG The Rock City Parish is a place where God dwells and visit other places</p>
          </div>
        </div>
        <div class="row margin-t-30">
          <div class="col-lg-4 margin-t-20">
            <div class="services-box">
              <div class="media">
                <i class="pe-7s-notebook text-custom"></i>
                <div class="media-body ml-4">
                  <h4>Sunday Workers Meeting</h4>
                  <p>
                    7:00 AM - 7:30 AM
                  </p>
                  <p
                    class="pt-2 text-muted"
                  >Some quick example text to build on the card title and make up the bulk of the card's content. Moltin gives you the platform.</p>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-4 margin-t-20">
            <div class="services-box">
              <div class="media">
                <i class="pe-7s-notebook text-custom"></i>
                <div class="media-body ml-4">
                  <h4> 1st Service (Business Service)</h4>
                  <p>
                    7:30 AM - 8:30 AM
                  </p>
                  <p
                    class="pt-2 text-muted"
                  >Credibly brand standards compliant users without extensible services. Anibh euismod tincidunt ut laoreet Ipsum passage.</p>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-4 margin-t-20">
            <div class="services-box">
              <div class="media">
                <i class="pe-7s-notebook text-custom"></i>
                <div class="media-body ml-4">
                  <h4>Sunday School</h4>
                  <p>Sunday <br />
                  8:30 AM - 9:30 AM</p>
                  <p
                    class="pt-2 text-muted"
                  >Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean necessary regelialia.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-4 margin-t-20">
            <div class="services-box">
              <div class="media">
                <i class="pe-7s-notebook text-custom"></i>
                <div class="media-body ml-4">
                  <h4>2nd Service</h4>
                  <p>Sunday <br/>
                  9:30 AM - 11:30 AM</p>                 
                   <p
                    class="pt-2 text-muted"
                  >It is a paradisematic country, in which roasted parts of sentences fly into your mouth leave for the far World.</p>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-4 margin-t-20">
            <div class="services-box">
              <div class="media">
                <i class="pe-7s-notebook text-custom"></i>
                <div class="media-body ml-4">
                  <h4>House Fellowship</h4>
                  <p>Sunday <br/>
                  5:00 PM - 6:00 PM</p>
                  <p
                    class="pt-2 text-muted"
                  >Even the all-powerful Pointing has no control about the blind texts it is an almost unorthographic.</p>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-4 margin-t-20">
            <div class="services-box">
              <div class="media">
                <i class="pe-7s-notebook text-custom"></i>
                <div class="media-body ml-4">
                <h4>Potters House</h4>
                  <p>Monday <br/>
                  6:30 PM - 8:00 PM</p>
                  <p
                    class="pt-2 text-muted"
                  >Question Marks and devious Semikoli, but the Little Blind Text didn’t listen. She packed her seven versalia.</p>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="row">
          <div class="col-lg-4 margin-t-20">
            <div class="services-box">
              <div class="media">
                <i class="pe-7s-notebook text-custom"></i>
                <div class="media-body ml-4">
                  <h4>Digging Deep</h4>
                  <p> Tuesday<br/>
                  6:00 PM - 7:30 PM</p>
                  <p
                    class="pt-2 text-muted"
                  >There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration.</p>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-4 margin-t-20">
            <div class="services-box">
              <div class="media">
                <i class="pe-7s-notebook text-custom"></i>
                <div class="media-body ml-4">
                  <h4>Daughters of Zion</h4>
                  <p>Wednesday<br />
                  6:00 PM - 7:00 PM

                  </p>
                  <p
                    class="pt-2 text-muted"
                  >Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur.</p>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-4 margin-t-20">
            <div class="services-box">
              <div class="media">
                <i class="pe-7s-notebook text-custom"></i>
                <div class="media-body ml-4">
                  <h4>Faith Clinic</h4>
                  <p>Thursday
                    <br />
                    6:00 PM - 7:30 PM
                  </p>
                  
                  <p
                    class="pt-2 text-muted"
                  >All the Lorem Ipsum generators on the Internet tend to repeat predefined chunks as necessary.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!--START SERVICES-->

    <!--START WEBSITE-DESCRIPTION-->
    <section
      class="section bg-web-desc"
      :style="{'background-image': 'url(' + require('@/assets/images/img-1.jpg') + ')', 'background-size': 'cover','background-position': 'center'}"
    >
      <div class="bg-overlay"></div>
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="text-white">Join One of our Service Today</h2>
            <p
              class="padding-t-15 home-desc mx-auto"
            >Home to where God dwells and visit other places.</p>
            <a
              href="#"
              class="btn btn-bg-white margin-t-30"
            >Join Us</a>
          </div>
        </div>
      </div>
    </section>
    <!--END WEBSITE-DESCRIPTION-->
  </div>
</template>