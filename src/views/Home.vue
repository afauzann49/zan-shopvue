<template>
  <div class="home">
    <!-- Header Section Begin -->
    <Header />
    <!-- Header End -->

    <!-- Hero Section Begin -->
    <Hero />
    <!-- Hero Section End -->

    <!-- Women Banner Section Begin -->
    <Banner />
    <!-- Women Banner Section End -->

    <!-- Instagram Section Begin -->
    <Instagram />
    <!-- Instagram Section End -->

    <!-- Partner Section Begin -->
    <Partner />
    <!-- Partner Section End -->

    <!-- Footer Section Begin -->
    <Footer />
    <!-- Footer Section End -->
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Header from "@/components/Header.vue";
import Hero from "@/components/Hero.vue";
import Banner from "@/components/Banner.vue";
import Instagram from "@/components/Instagram.vue";
import Partner from "@/components/Partner.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    // HelloWorld
    Header,
    Hero,
    Banner,
    Instagram,
    Partner,
    Footer
  },
};
</script>
