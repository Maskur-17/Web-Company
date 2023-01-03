<template>

  <div>
    <Slider />

    <Aboutus />

    <OurServices />

    <div class="py-5">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col text-center my-auto">
            <div class="card">
              <h5 class="card-header bg-primary text-light">Contact Us</h5>
              <div class="card-body">
                <h5 class="card-title">If you have any queries ?</h5>
                <p class="card-text">Please Reach out us at contact dimaskurniawan22@gmail.com</p>
                <nuxt-link to="/contact" class="px-5 btn btn-primary">Contact Us</nuxt-link>
              </div>
            </div>
            
          </div>
        </div>
      </div>
    </div>

  </div>
</template>

<script>

import Slider from '~/components/Slider.vue';
import Aboutus from '~/components/Aboutus.vue';
import OurServices from '~/components/OurServices.vue';

export default {
  name: 'IndexPage',
  components: { Slider, Aboutus, OurServices },
  head() {
    return {
      title: 'Home Page',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Web Company - Home Page'
        },
        {
          hid: 'keywords',
          name: 'keywords',
          content: 'Apartement Signature - Home Page'
        }
      ]
    }
  }
}
</script>
