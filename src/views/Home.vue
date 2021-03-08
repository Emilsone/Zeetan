<template>
  <div class="home">
   <NavBar />
   <HeroContent />
   <WhyChoose />
   <NotifiedEvent />
  </div>
</template>

<script>
// @ is an alias to /src
import NavBar from "@/components/NavBar.vue";
import HeroContent from "@/components/HeroContent.vue";
import WhyChoose from "@/components/WhyChoose.vue";
import NotifiedEvent from "@/components/NotifiedEvent.vue";

export default {
  name: "Home",
  components: {
    NavBar,
    HeroContent,
    WhyChoose,
    NotifiedEvent
  }
};
</script>
