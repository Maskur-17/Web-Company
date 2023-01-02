<template>
  <div>
    <div class="py-5 bg-warning">
      <div class="container text-center">
        <h1>About Us</h1>
      </div>
    </div>

    <Aboutus />

  </div>
</template>

<script>
import Aboutus from '~/components/Aboutus.vue'

export default {
  name: 'about',
  components: { Aboutus },
  head() {
    return {
      title: 'About Us',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Web Company'
        },
        {
          hid: 'keywords',
          name: 'keywords',
          content: 'Apartement Signature'
        }
      ]
    }
  }
}
</script>
