<template>
  <div>
    <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
          aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner" style="max-height: 720px ;" >
        <div class="carousel-item active">
          <img src="/images/img-1.jpg" class="d-block w-100" alt="img-1.jpg">
          <div class="carousel-caption d-none d-md-block">
            <h5>Work With Us & Get Best Services</h5>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam, sint.</p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="/images/img-2.jpg" class="d-block w-100" alt="img-2.jpg">
          <div class="carousel-caption d-none d-md-block">
            <h5>Professional Workplace</h5>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum soluta aliquam facere vel?.</p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="/images/img-3.jpg" class="d-block w-100" alt="img-3.jpg">
          <div class="carousel-caption d-none d-md-block">
            <h5>Supportive Environment</h5>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
          </div>
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'slider'
}
</script>
