<script setup>
import { RouterView } from "vue-router";
import Navbar from "@/components/Navbar.vue";
</script>

<template>
  <Navbar />
  <RouterView />
</template>




<link href='https://fonts.googleapis.com/css?family=Inter' rel='stylesheet'></link>
<style>
* {
  /* global reset */
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
html {
  /* 10px / 16px * 100% = 62.5% */
  font-size: 62.5%;
  overflow-x: hidden;
  scroll-behavior: smooth;
}

body {
  /* for now no specific typface */
  /* coz i need to build few pages first */
  font-family: 'Inter';
  /* reset height and weight */
  line-height: 1;
  font-weight: 400;
  /* personal base color */
  color: #555;

  /* Only works if there is nothing absolutely
  positioned in relation to body */
  overflow-x: hidden;
}

/* **************************** */
/* GENERAL REUSEABLE COMPONENTS */
/* **************************** */
.container {
  /* 1140px */
  max-width: 120rem;
  margin: 0 auto;
  padding: 0 4.8rem;
}

.grid {
  display: grid;
  row-gap: 9.6rem;
  column-gap: 6.4rem;
}

.grid:not(:last-child) {
  margin-bottom: 9.6rem;
}

.grid--2cols {
  grid-template-columns: repeat(2, 1fr);
}

.grid--3cols {
  grid-template-columns: repeat(3, 1fr);
}

.grid--4cols {
  grid-template-columns: repeat(4, 1fr);
}

.grid--5cols {
  grid-template-columns: repeat(5, 1fr);
}

.grid--center-v {
  align-items: center;
}

.heading-primary,
.heading-secondary,
.heading-tertiary {
  font-weight: 700;
  color: #333;
  letter-spacing: -0.5px;
}

.heading-primary {
  font-size: 5rem;
  line-height: 1.05;
  /* margin-bottom: 3.2rem; */
  color: black;
}

.heading-secondary {
  font-size: 4rem;
  line-height: 1.2;
  color: black;
  margin-bottom: 1rem;
}

.heading-tertiary {
  font-size: 2rem;
  line-height: 1.2;
  margin-bottom: 0.2rem;
}

.subheading {
  display: block;
  font-size: 1.6rem;
  font-weight: 500;
  color: #1f5dcf;
  text-transform: uppercase;
  margin-bottom: 1.6rem;
  letter-spacing: 0.75px;
}

.btn,
.btn:link,
.btn:visited {
  display: inline-block;

  text-decoration: none;
  font-size: 1.5rem;
  font-weight: 500;
  padding: 1rem 2rem;
  border-radius: 3px;

  /* onlu for btn itself */
  border: none;
  cursor: pointer;
  font-family: inherit;
  /* Put transition on original state */
  /* transition: background-color 0.3s; */
  transition: all 0.3s;
}

.btn--full:link,
.btn--full:visited {
  color: black;
  background-color: #D9D9D9;
}

.btn--full:hover,
.btn--full:active {
  background-color: #b4b4b4;
}

.btn--outline:link,
.btn--outline:visited {
  color: #555;
  background-color: #fff;
}

.btn--outline:hover,
.btn--outline:active {
  background-color: #e9f0fd;
  /* to add border inside */
  box-shadow: inset 0 0 0 3px #fff;
}

.btn--form {
  background-color: #0a1f45;
  color: #e9f0fd;
  align-self: end;
  padding: 1.2rem;
}

.btn--form:hover {
  background-color: #fff;
  color: #0a1f45;
}

.link {
  transition: all 0.4ms;
}

.link:link,
.link:visited {
  display: inline-block;
  color: #2267e6;
  text-decoration: none;
  border-bottom: 1px solid currentColor;
  padding-bottom: 2px;
  transition: all 0.3s;
}

.link:hover,
.link:active {
  color: #1f5dcf;
  border-bottom: 1px solid transparent;
}

.list {
  list-style: none;
  display: flex;
  flex-direction: column;
  gap: 1.6rem;
}

.list-item {
  font-size: 1.8rem;
  display: flex;
  align-items: center;
  gap: 1.6rem;
  line-height: 1.2;
}

.list-icon {
  width: 3rem;
  height: 3rem;
  color: #2267e6;
}

*:focus {
  /* outline: none; */
  /* outline: 4px dotted #2267e6; */
  /* outline-offset: 4px */
  box-shadow: 0 0 0 0.8rem rgba(34, 103, 230, 0.5);
}

/* HELPER/SETTING CLASSES */
.margin-right-sm {
  margin-right: 1.6rem !important;
}
.margin-bottom-md {
  margin-bottom: 4.8rem !important;
}

.center-text {
  text-align: center;
}

.rectangle{
  background-color: #BBB8B8;
  width: 15rem;
  height: 0.8rem;
  margin-bottom: 5rem;
}

.pagination-container{
  display: flex;
  justify-content: center;
  gap: 0.5rem;
}
.pagination{
  font-size: 1.5rem;
  margin-bottom: 5rem;
}


</style>
