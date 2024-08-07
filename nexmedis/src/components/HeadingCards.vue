<script setup></script>

<template>
  <div class="container grid grid--4cols">
    <div class="feature">
      <i class="pi pi-android" name="laptop-outline"></i>
      <h3 class="heading-tertiary">Heading Line</h3>
      <p class="feature-text">
        Lörem ipsum kvasirtad sön huruvida pohönera set. Båbire ultragen
      </p>
    </div>
    <div class="feature">
      <i class="pi pi-apple" name="book-outline"></i>
      <h3 class="heading-tertiary">Heading Line</h3>
      <p class="feature-text">
        Lörem ipsum kvasirtad sön huruvida pohönera set. Båbire ultragen
      </p>
    </div>
    <div class="feature">
      <i class="pi pi-discord" name="checkmark-done-outline"></i>
      <h3 class="heading-tertiary">Heading Line</h3>
      <p class="feature-text">
        Lörem ipsum kvasirtad sön huruvida pohönera set. Båbire ultragen
      </p>
    </div>
    <div class="feature">
      <i class="pi pi-google" name="build-outline"></i>
      <h3 class="heading-tertiary">Heading Line</h3>
      <p class="feature-text">
        Lörem ipsum kvasirtad sön huruvida pohönera set. Båbire ultragen
      </p>
    </div>
  </div>
</template>

<style scoped>
.pi {
  color: black;
  font-size: 3.2rem;
  background-color: #a1a0a0;
  padding: 1.6rem;
  border-radius: 50%;
  margin-bottom: 2rem;
}
.feature {
  padding: 3rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 1rem;
  background-color: #d9d9d9;
}
.heading-tertiary {
  text-align: center;
}
.feature-text {
  font-size: 1.4rem;
}
</style>
