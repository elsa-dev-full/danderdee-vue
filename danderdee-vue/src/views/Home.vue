<template>
  <div>
    <!-- header section -->
    <Header />
    <!-- end of header section -->

    <!-- One slider section -->
    <OneSlide />
    <!-- end of one slider section -->

    <!-- slider section -->
    <Slider />
    <!-- end of slider section -->    

    <!-- free wifi section -->
    <Freebox />
    <!-- end of free wifi section -->

    <!-- contact section -->
    <ContactForm id="contact" />
    <!-- end of contact section -->
  </div>
</template>

<script>
import Header from "../sections/Header_home";
import Freebox from "../sections/Freebox_home";
import Slider from "../components/Slider_home";
import OneSlide from "../components/OneSlide_home";
import ContactForm from "../sections/ContactForm";

export default {
  name: "Home",
  components: {
    Header,
    Freebox,
    Slider,
    OneSlide,
    ContactForm
  }
};
</script>