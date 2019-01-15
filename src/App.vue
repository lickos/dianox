<template>
  <div>
    <app-header></app-header>
    <app-carousel></app-carousel>
    <app-welcome></app-welcome>
    <app-section1></app-section1>
    <app-services></app-services>
    <app-about></app-about>
    <app-contact></app-contact>
    <app-footer></app-footer>
  </div>
</template>

<script>
import Header from "./components/Header";
import Carousel from "./components/Carousel";
import Welcome from "./components/welcome";
import Section1 from "./components/section1";
import Services from "./components/Services";
import About from "./components/About";
import Contact from "./components/Contact";
import Footer from "./components/Footer";

export default {
  name: "app",
  components: {
    "app-header": Header,
    "app-carousel": Carousel,
    "app-welcome": Welcome,
    "app-section1": Section1,
    "app-services": Services,
    "app-about": About,
    "app-contact": Contact,
    "app-footer": Footer
  }
};
</script>

<style>
* {
  font-family: "Ubuntu Condensed", sans-serif;
}
</style>
