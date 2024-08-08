<script setup>
import PopService from "../assets/popservice.jpg";
</script>
<template>
  <section class="section-home-services">
    <div class="container">
      <h2 class="heading-secondary">Most Needed Home Service</h2>
      <p class="rectangle">&nbsp;</p>
      <div class="grid grid--4cols">
        <div class="home-service">
          <div class="home-service-img-container">
            <img
              :src="`${PopService}`"
              alt="Service Image"
              class="home-service-img"
            />
          </div>
          <div class="home-service-container">
            <div class="home-service-profile">
              <img :src="`${PopService}`" class="company-img" />
              <p class="company-description">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta
                animi eaque facere?
              </p>
            </div>
            <div class="home-service-button">
              <a class="btn btn--full" href="#">Message</a>
              <a class="btn btn--full" href="#">View More</a>
            </div>
          </div>
        </div>
        <div class="home-service">
          <div class="home-service-img-container">
            <img
              :src="`${PopService}`"
              alt="Service Image"
              class="home-service-img"
            />
          </div>
          <div class="home-service-container">
            <div class="home-service-profile">
              <img :src="`${PopService}`" class="company-img" />
              <p class="company-description">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta
                animi eaque facere?
              </p>
            </div>
            <div class="home-service-button">
              <a class="btn btn--full" href="#">Message</a>
              <a class="btn btn--full" href="#">View More</a>
            </div>
          </div>
        </div>
        <div class="home-service">
          <div class="home-service-img-container">
            <img
              :src="`${PopService}`"
              alt="Service Image"
              class="home-service-img"
            />
          </div>
          <div class="home-service-container">
            <div class="home-service-profile">
              <img :src="`${PopService}`" class="company-img" />
              <p class="company-description">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta
                animi eaque facere?
              </p>
            </div>
            <div class="home-service-button">
              <a class="btn btn--full" href="#">Message</a>
              <a class="btn btn--full" href="#">View More</a>
            </div>
          </div>
        </div>
        <div class="home-service">
          <div class="home-service-img-container">
            <img
              :src="`${PopService}`"
              alt="Service Image"
              class="home-service-img"
            />
          </div>
          <div class="home-service-container">
            <div class="home-service-profile">
              <img :src="`${PopService}`" class="company-img" />
              <p class="company-description">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta
                animi eaque facere?
              </p>
            </div>
            <div class="home-service-button">
              <a class="btn btn--full" href="#">Message</a>
              <a class="btn btn--full" href="#">View More</a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="pagination-container">
      <i class="pi pi-circle-fill pagination"></i>
      <i class="pi pi-circle pagination"></i>
    </div>
  </section>
</template>
<style scoped>
.grid {
  margin-bottom: 2rem;
}
.home-service-img {
  height: 15rem;
  width: 100%;
  object-fit: cover;
}
.home-service {
  display: flex;
  flex-direction: column;
  background-color: #d9d9d9;
}
.home-service-container {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  padding: 1rem;
}
.home-service-profile {
  display: flex;
  gap: 2rem;
  align-items: center;
}
.company-img {
  border-radius: 20rem;
  width: 5rem;
  height: 5rem;
}
.home-service-button {
  display: flex;
  gap: 1rem;
}
.btn,
.btn:link,
.btn:visited {
  font-size: 1.4rem;
  font-weight: 500;
  padding: 0.5rem 1rem;
  background-color: #aeacac;
}

@media (max-width: 65em) {
  .grid--4cols {
    grid-template-columns: repeat(2, 1fr);
  }
}
</style>
