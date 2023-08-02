<template>
  <div id="app">
    <Home/>
    <ContactMe/>
    <CommunityManager/>
    <Copywriting/>
    <DigitalDesign/>
    <CommunityManagerServices/>
    <CopyWriterServices/>
    <DigitalDesignerServicesVue/>
    <ProfessionalProyects/>
    <PhraseVue/>
  </div>
</template>

<script>
import Home from './components/Home.vue';
import ContactMe from './components/ContactMe.vue';
import CommunityManager from './components/CommunityManager.vue';
import Copywriting from './components/Copywriting.vue';
import DigitalDesign from './components/DigitalDesign.vue';
import CommunityManagerServices from './components/CommunityManagerServices.vue';
import CopyWriterServices from './components/CopyWriterServices.vue';
import DigitalDesignerServicesVue from './components/DigitalDesignerServices.vue';
import ProfessionalProyects from './components/ProfessionalProyects.vue';
import PhraseVue from './components/Phrase.vue';

export default {
  components: {
    Home,
    ContactMe,
    CommunityManager,
    Copywriting,
    DigitalDesign,
    CommunityManagerServices,
    CopyWriterServices,
    DigitalDesignerServicesVue,
    ProfessionalProyects,
    PhraseVue,
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Caveat&display=swap');
@import url('https://fonts.cdnfonts.com/css/aileron');
body {
  margin: 0px;
}
</style>
