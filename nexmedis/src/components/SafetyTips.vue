<script setup>
import PopService from "../assets/popservice.jpg";
</script>
<template>
  <section class="section-safety-tips">
    <div class="container">
      <h2 class="heading-secondary">View Safety Tips</h2>
      <div class="grid grid--2cols">
        <div class="safety-tips-card">
          <p class="safety-tips-description">
            <strong
              >Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi
              quos eius blanditiis temporibus tempore cum quibusdam
              exercitationem harum, officia numquam magnam doloremque sunt unde,
              praesentium aliquam ipsum? Officia, iste culpa!</strong
            >
          </p>
          <a class="btn btn--full btns" href="#">Learn More</a>
        </div>
        <div class="safety-tips-card">
          <p class="safety-tips-description">
            <strong
              >Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi
              quos eius blanditiis temporibus tempore cum quibusdam
              exercitationem harum, officia numquam magnam doloremque sunt unde,
              praesentium aliquam ipsum? Officia, iste culpa!</strong
            >
          </p>
          <a class="btn btn--full btns" href="#">Learn More</a>
        </div>
      </div>

      <div class="grid grid--2cols">
        <div>
          <h2 class="heading">Heading</h2>
          <div class="safety-tips-container">
            <div class="safety-tips-paragraph">
              <p class="paragraph"><strong>lorem ipsum</strong></p>
              <p class="paragraph">
                adipisicing elit. Sapiente delectus similique dicta! Eveniet
                tenetur.
              </p>
              <p class="paragraph"><strong>lorem ipsum</strong></p>
              <p class="paragraph">
                adipisicing elit. Sapiente delectus similique dicta! Eveniet
                tenetur.
              </p>
            </div>
            <a class="btn btn--full" href="#">Book a Contractor</a>
          </div>
        </div>
        <div>
          <img :src="`${PopService}`" alt="Service Image" class="card__image" />
        </div>
        <div>
          <img :src="`${PopService}`" alt="Service Image" class="card__image" />
        </div>
        <div>
          <h2 class="heading">Heading</h2>
          <div class="safety-tips-container">
            <div class="safety-tips-paragraph">
              <p class="paragraph"><strong>lorem ipsum</strong></p>
              <p class="paragraph">
                adipisicing elit. Sapiente delectus similique dicta! Eveniet
                tenetur.
              </p>
              <p class="paragraph"><strong>lorem ipsum</strong></p>
              <p class="paragraph">
                adipisicing elit. Sapiente delectus similique dicta! Eveniet
                tenetur.
              </p>
            </div>
            <a class="btn btn--full" href="#">Become a Seller</a>
          </div>
        </div>
      </div>
    </div>
    <div class="safety-registered-container">
      <h2 class="heading-register divider">100+ Registerd Companies</h2>
      <h2 class="heading-register">2999 Registerd Members</h2>
    </div>
  </section>
</template>

<style scoped>
.section-safety-tips {
  padding-bottom: 20rem;
  position: relative;
}
.grid {
  align-items: center;
  justify-content: center;
}
.heading-secondary {
  text-align: center;
  margin-bottom: 3rem;
}
.safety-tips-card {
  padding: 1.5rem;
  background-color: #d9d9d9;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 1rem;
}
.safety-tips-description {
  line-height: 2rem;
  font-size: 1.4rem;
}
.btns {
  background-color: #a09999;
  color: black;
}
.heading {
  font-size: 4rem;
  line-height: 1.2;
  color: black;
  margin-bottom: 1rem;
  font-weight: 700;
  margin-bottom: 2rem;
}
.heading-register {
  font-size: 4rem;
  line-height: 1.2;
  color: black;
  font-weight: 700;
}
.paragraph {
  font-size: 1.8rem;
  color: black;
}
.safety-tips-container {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  align-items: center;
  justify-content: center;
}
.safety-tips-paragraph {
  line-height: 3rem;
}

.safety-registered-container {
  bottom: -5rem;
  left: 50%;
  transform: translate(-50%, 0);
  width: 80rem;
  position: absolute;
  background-color: white;
  padding: 2.5rem 5rem;
  display: flex;
  gap: 1rem;
}
.divider {
  border-right: 0.5rem black solid;
}
</style>
