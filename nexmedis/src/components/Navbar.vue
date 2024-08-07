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
        <li><a class="btn btn--full" href="#">Sign In</a></li>
        <li><a class="btn btn--full" href="#">Sign Up</a></li>
        <li>
          <a class="btn btn--full aa" href="#"
            ><strong>Become a Seller</strong></a
          >
        </li>
      </ul>
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
</style>
