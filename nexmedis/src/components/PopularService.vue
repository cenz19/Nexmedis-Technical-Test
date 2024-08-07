<script setup>
import PopService from "../assets/popservice.jpg";
</script>

<template>
  <section class="section-popular-service">
    <div class="container">
      <h2 class="heading-secondary">Popular Service</h2>
      <p class="rectangle">&nbsp;</p>
      <div class="grid grid--4cols">
        <div class="card">
          <img :src="`${PopService}`" alt="Service Image" class="card__image" />
        </div>
        <div class="card">
          <img :src="`${PopService}`" alt="Service Image" class="card__image" />
        </div>
        <div class="card">
          <img :src="`${PopService}`" alt="Service Image" class="card__image" />
        </div>
        <div class="card">
          <img :src="`${PopService}`" alt="Service Image" class="card__image" />
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
.container {
  margin-bottom: 2rem;
}
.card__image {
  object-fit: cover;
  width: 100%;
  height: auto;
}
</style>
