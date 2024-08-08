<script setup>
import PopService from "../assets/popservice.jpg";
</script>
<template>
  <section class="section-nearby-companies">
    <div class="container">
      <h2 class="heading-secondary">Nearby Companies</h2>
      <p class="rectangle">&nbsp;</p>
      <div class="grid grid--3cols">
        <div class="company">
          <div class="company-profile">
            <img :src="`${PopService}`" class="company-img" />
            <p class="company-description">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta
              animi eaque facere? Earum mollitia impedit voluptas.
            </p>
          </div>
          <div class="company-about">
            <h3 class="heading-tertiary">About</h3>
            <p class="company-description">
              Lörem ipsum kvasirtad sön huruvida pohönera set. Båbire ultragen
              Lörem ipsum kvasirtad sön huruvida
            </p>
          </div>
          <div class="company-button">
            <a class="btn btn--full" href="#">Message</a>
            <a class="btn btn--full" href="#">View More</a>
          </div>
        </div>
        <div class="company">
          <div class="company-profile">
            <img :src="`${PopService}`" class="company-img" />
            <p class="company-description">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta
              animi eaque facere? Earum mollitia impedit voluptas.
            </p>
          </div>
          <div class="company-about">
            <h3 class="heading-tertiary">About</h3>
            <p class="company-description">
              Lörem ipsum kvasirtad sön huruvida pohönera set. Båbire ultragen
              Lörem ipsum kvasirtad sön huruvida
            </p>
          </div>
          <div class="company-button">
            <a class="btn btn--full" href="#">Message</a>
            <a class="btn btn--full" href="#">View More</a>
          </div>
        </div>
        <div class="company">
          <div class="company-profile">
            <img :src="`${PopService}`" class="company-img" />
            <p class="company-description">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta
              animi eaque facere? Earum mollitia impedit voluptas.
            </p>
          </div>
          <div class="company-about">
            <h3 class="heading-tertiary">About</h3>
            <p class="company-description">
              Lörem ipsum kvasirtad sön huruvida pohönera set. Båbire ultragen
              Lörem ipsum kvasirtad sön huruvida
            </p>
          </div>
          <div class="company-button">
            <a class="btn btn--full" href="#">Message</a>
            <a class="btn btn--full" href="#">View More</a>
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
.company {
  background-color: #d9d9d9;
  padding: 2rem;
}
.company-profile {
  display: flex;
  gap: 2rem;
  align-items: center;
  margin-bottom: 4rem;
}
.company-img {
  border-radius: 20rem;
  width: 8rem;
  height: 8rem;
}
.company-description {
  font-size: 1.2rem;
  color: black;
}
.company-about {
  margin-bottom: 2rem;
}

.company-button {
  display: flex;
  gap: 1rem;
}
.btn {
  background-color: #bfbcbc;
}
.container {
  margin-bottom: 2rem;
}
@media (max-width: 65em) {
  .grid {
    display: grid;
    row-gap: 1rem;
    column-gap: 1rem;
  }
  .btn {
    font-size: 1.2rem;
  }
}
</style>
