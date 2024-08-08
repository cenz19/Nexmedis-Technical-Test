<script setup></script>

<template>
  <header class="header">
    <a href="#">
      <p class="logo"><strong>LOGO</strong></p>
    </a>
    <div class="service-nav">
      <ul class="service-nav-list">
        <li>
          <a class="service-list" href="#"
            >Service Category 1<i class="pi pi-angle-down"></i
          ></a>
        </li>
        <li>
          <a class="service-list" href="#"
            >Service Category 2<i class="pi pi-angle-down"></i
          ></a>
        </li>
      </ul>
    </div>
    <div class="button-nav">
      <ul class="button-nav-list">
        <li><a class="btn btn--full btn-text" href="#">Sign In</a></li>
        <li><a class="btn btn--full btn-text" href="#">Sign Up</a></li>
        <li>
          <a class="btn btn--full btn-text" href="#"
            ><strong>Become a Seller</strong></a
          >
        </li>
      </ul>
    </div>
    <div class="hamburger">
      <i class="pi pi-bars"></i>
    </div>
  </header>
</template>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #e8e8e8;
  height: 9.6rem;
  padding: 4.8rem;
  position: relative;
}

.logo {
  font-size: 2rem;
  font-weight: 600;
  background-color: #d9d9d9;
  color: black;
  padding: 1rem 3rem;
}
.service-nav-list {
  list-style: none;
  display: flex;
  align-items: center;
  gap: 2.5rem;
}

.button-nav-list {
  list-style: none;
  display: flex;
  align-items: center;
  gap: 1rem;
}

.service-list {
  font-size: 1.5rem;
  color: black;
}
.hamburger {
  display: none;
}

/* Bellow 1120 px */
@media (max-width: 70em) {
  .service-list {
    font-size: 1.3rem;
    color: black;
  }

  .btn,
  .btn:link,
  .btn:visited {
    font-size: 1rem;
    /* font-size: 1.5rem; */
  }
}

@media (max-width: 52.5em) {
  .button-nav-list {
    display: none;
  }
  .hamburger {
    display: block;
    font-size: 2.5rem;
  }
}
</style>
