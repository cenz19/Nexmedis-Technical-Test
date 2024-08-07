<script setup></script>
<template>
  <section class="section-footer">
    <div class="container">
      <div class="grid grid--3cols">
        <div>
          <a href="#">
            <p class="logo"><strong>LOGO</strong></p>
          </a>
          <p class="paragraph">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam,
            alias ratione. Nobis quis quia fugit? Unde exercitationem et maiores
            nostrum deserunt.
          </p>
          <div class="icon-container">
            <i class="pi pi-android" name="laptop-outline"></i>
            <i class="pi pi-apple" name="laptop-outline"></i>
            <i class="pi pi-discord" name="laptop-outline"></i>
          </div>
          <div class="btn-container">
            <a class="btn btn--full" href="#">lorem</a>
            <a class="btn btn--full" href="#">lorem</a>
          </div>
        </div>
        <div>
          <h2 class="heading">Lorem Epsum</h2>
          <p class="paragraph">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Facilis
            accusantium optio laboriosam deserunt! Eaque reiciendis numquam quam
            natus optio sunt voluptatem atque nesciunt cupiditate, sint
            explicabo dolores eius minus quod?
          </p>
        </div>
        <div>
          <h2 class="heading">Lorem Epsum</h2>
          <p class="paragraph">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Facilis
            accusantium optio laboriosam deserunt! Eaque reiciendis numquam quam
            natus optio sunt voluptatem atque nesciunt cupiditate, sint
            explicabo dolores eius minus quod?
          </p>
        </div>
      </div>
    </div>
    <div class="divider">&nbsp;</div>
  </section>
</template>

<style scoped>
.section-footer {
  background-color: #989191;
}
.container {
  padding: 10rem 4.8rem 4.8rem 4.8rem;
}
.logo {
  display: inline-block;
  font-size: 2rem;
  font-weight: 600;
  background-color: #d9d9d9;
  color: black;
  padding: 1rem 3rem;
  margin-bottom: 6rem;
}
.paragraph {
  font-size: 1.6rem;
  color: #484545;
  margin-bottom: 3rem;
}
.pi {
  color: black;
  font-size: 1.6rem;
  background-color: #a1a0a0;
  padding: 0.8rem;
  border-radius: 50%;
  margin-bottom: 2rem;
}
.icon-container,
.btn-container {
  display: flex;
  justify-content: space-around;
}
.heading {
  font-size: 3rem;
  color: black;
  margin-bottom: 1rem;
  font-weight: 700;
  margin-bottom: 2rem;
}
.divider {
  height: 4rem;
  background-color: #252424;
}
</style>
