<template>
  <div>
    <div class="py-5 bg-warning">
      <div class="container text-center">
        <h1>About Us</h1>
      </div>
    </div>

    <Aboutus />

    <div class="container mb-5">
      <hr>
      <div class="row justify-content-start">
        <h2 class="text-center mb-3">Our Stories</h2>
        <div class="col-6">
          <img src="/images/img-3.jpg" class="img-thumbnail w-100 shadow" alt="Apartement Jaya"/>
        </div>
        <div class="col-6">
          <b>Lorem ipsum dolor sit amet,</b> consectetur adipisicing elit. Sint saepe perspiciatis cupiditate amet dolorum iusto error asperiores tempora optio unde laborum ad deleniti repellendus qui, cumque officiis eaque, consequuntur excepturi illum harum, quas reiciendis quae. Dolore, accusamus cum a quia illo deserunt corporis quidem quos culpa dicta repudiandae nobis placeat. Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas nihil odit itaque culpa hic corporis, autem vel velit dolorem minima. Lorem ipsum dolor sit, amet consectetur adipisicing elit. Excepturi doloremque saepe, at voluptatum, alias vel unde nobis ab tempore natus dolor id debitis sequi ullam animi. Eaque debitis alias error.
        </div>
      </div>
    </div>

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
