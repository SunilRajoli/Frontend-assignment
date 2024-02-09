<template>
  <div id="app">
    <NavigationBar />
    <TechServicesSection />
    <SectionTwo />
    <SectionThree />
    <SectionFour />
    <SectionFive />
    <SectionSix />
    <SectionSeven />
    <SectionEight />
    <FooterBar />
    <!-- Other components or content of your application -->
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import NavigationBar from './components/NavigationBar.vue';
import TechServicesSection from './components/TechServicesSection.vue';
import SectionTwo from './components/SectionTwo.vue';
import SectionThree from './components/SectionThree.vue';
import SectionFour from './components/SectionFour.vue';
import SectionFive from './components/SectionFive.vue';
import SectionSix from './components/SectionSix.vue';
import SectionSeven from './components/SectionSeven.vue';
import SectionEight from './components/SectionEight.vue';
import FooterBar from './components/FooterBar.vue';

export default defineComponent({
  name: 'App',
  components: {
    NavigationBar,
    TechServicesSection,
    SectionTwo,
    SectionThree,
    SectionFour,
    SectionFive,
    SectionSix,
    SectionSeven,
    SectionEight,
    FooterBar
  },
});
</script>

<style>
body {
  overflow-x: hidden;
}


/* Add global styles here if needed */
</style>
