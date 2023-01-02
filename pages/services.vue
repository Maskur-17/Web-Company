<template>
  <div>
    <div class="py-5 bg-warning">
      <div class="container text-center">
        <h3>Our Services</h3>
      </div>
    </div>

    <OurServices />
  </div>
</template>

<script>
import OurServices from '~/components/OurServices.vue'

export default {
  name: 'services',
  components: { OurServices },
  head() {
    return {
      title: 'OurServices',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Web Company - OurServices',
        },
        {
          hid: 'keywords',
          name: 'keywords',
          content: 'Apartement - Our Services'
        }
      ]
    }
  }
}
</script>

<style>

</style>
