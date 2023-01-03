<template>
  <div>
    <div class="py-5 bg-warning">
      <div class="container text-center">
        <h3>Contact</h3>
      </div>
    </div>
    <div class="py-5">
      <div class="container">
        <h1 class="text-center"> Our Teams</h1>
        <div class="row my-5 justify-content-center">
          <div class="col-4">
            <div class="card">
              <img src="images/profile-1.jpg" class="card-img-top" alt="ourteams">
              <div class="card-body">
                <h5 class="card-title">Faizal Abdul Hakim</h5>
                <h6 class="card-subtitle mb-2 text-muted">CEO Company</h6>
                <p class="card-text">Lorem ipsum dolor sit amet.
                </p>
              </div>
            </div>
          </div>
          <div class="col-4">
            <div class="card">
              <img src="images/profile-2.jpg" class="card-img-top" alt="ourteams">
              <div class="card-body">
                <h5 class="card-title">Angelina</h5>
                <h6 class="card-subtitle mb-2 text-muted">Director of Finance</h6>
                <p class="card-text">Lorem ipsum dolor sit amet Lorem, ipsum..
                </p>
              </div>
            </div>
          </div>
          <div class="col-4">
            <div class="card">
              <img src="images/profile-3.jpg" class="card-img-top" alt="ourteams">
              <div class="card-body">
                <h5 class="card-title">Dimas Kurniawan</h5>
                <h6 class="card-subtitle mb-2 text-muted">Manager Marketing</h6>
                <p class="card-text">Lorem ipsum dolor sit amet.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="row justify-content-center">
          <div class="col text-center my-auto">
            <div class="card">
              <h5 class="card-header bg-primary text-light">Contact Us</h5>
              <div class="card-body">
                <h5 class="card-title">If you have any queries ?</h5>
                <p class="card-text">Please Reach out us at contact dimaskurniawan22@gmail.com</p>
                <nuxt-link to="/" class="px-5 btn btn-primary">Contact Us</nuxt-link>
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
