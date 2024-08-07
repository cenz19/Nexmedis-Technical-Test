<script setup>
import Background from "../assets/bg.jpg";
</script>

<template>
  <section
    class="section-hero"
    :style="{ backgroundImage: `url(${Background})` }"
  >
    <div class="hero-container container">
      <h1 class="heading-primary">
        We're Here To Make <br />
        Your Life Easier.
      </h1>
    </div>
    <div class="input-container container">
      <input type="text" class="input" />
      <button class="btn btn--full">Search</button>
    </div>
    <div class="heading-container">
      <h2 class="heading-secondary">Heading Line</h2>
      <p class="heading-paragraph">
        Lörem ipsum kvasirtad sön huruvida pohönera set. Båbire ultragen
        homodegon: deneheten ifall geoliga. Lyng kada. Vass fade stenoska. Etånt
        dossa alltså hypode vikydade.
      </p>
    </div>
  </section>
</template>

<style scoped>
.section-hero {
  position: relative;
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
  padding: 9rem 4.8rem 18rem 4.8rem;
  margin-bottom: 20rem;
}
.hero-container {
  margin-bottom: 4rem;
}
.input-container {
  margin-top: 2.4rem;
  display: flex;
}
.input {
  flex-grow: 1;
  padding: 1.2rem;
}
.btn--full {
  border: 1px solid black;
  padding: 1.6rem 3.2rem;
}

.heading-container {
  bottom: -10rem;
  left: 50%;
  transform: translate(-50%, 0);
  width: 65rem;
  position: absolute;
  background-color: white;
  padding: 2.5rem 5rem;
}
.heading-secondary {
  color: #333;
  margin-bottom: 1.2rem;
  text-align: center;
}

.heading-paragraph {
  line-height: 1.6;
  font-size: 1.6rem;
}
</style>
