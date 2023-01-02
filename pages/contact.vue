<template>
  <div>
    <div class="py-5 bg-warning">
      <div class="container text-center">
        <h3>Contact</h3>
      </div>
    </div>
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
export default {
  name: 'contact',
  head() {
    return {
      title: 'Contact Page',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Web Company - Contact Us'
        },
        {
          hid: 'keywords',
          name: 'keywords',
          content: 'Apartement Signature - Contact Us'
        }
      ]
    }
  }
}
</script>
