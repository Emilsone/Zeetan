<template>
  <div class="home">
   <NavBar />
   <HeroContent />
   <WhyChoose />
   <NotifiedEvent />
   <EasyDebugging />
   <HttpPage />
   <AdvanceFeature />
   <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import NavBar from "@/components/NavBar.vue";
import HeroContent from "@/components/HeroContent.vue";
import WhyChoose from "@/components/WhyChoose.vue";
import NotifiedEvent from "@/components/NotifiedEvent.vue";
import EasyDebugging from "@/components/EasyDebugging.vue";
import HttpPage from "@/components/HttpPage.vue";
import AdvanceFeature from "@/components/AdvanceFeature.vue";
import Footer from "@/components/Footer.vue";
export default {
  name: "Home",
  components: {
    NavBar,
    HeroContent,
    WhyChoose,
    NotifiedEvent,
    EasyDebugging,
    HttpPage,
    AdvanceFeature, 
    Footer
  }
};
</script>
