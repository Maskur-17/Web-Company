<template>

  <div>
    <Slider />

    <Aboutus />

    <OurServices />

    <div class="py-5">
      <div class="container">
        <div class="row">
          <div class="col-md-8">
            <h1 class="main-heading">If you have any queries ?</h1>
            <h4>Please Reach out us at contatc dimaskurniawan22@gmail.com</h4>
          </div>
          <div class="col-md-4 text-center my-auto">
            <nuxt-link to="/contact" class="px-5 btn btn-primary">Contact Us</nuxt-link>
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
