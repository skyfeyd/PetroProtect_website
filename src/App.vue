<script setup>
import NavBarVue from "./components/navBar.vue"
import MainVue from "./components/main.vue"
import PresentationVue from "./components/Presentation.vue"
import TeamVue from "./components/team.vue"
import ContactVue from "./components/contact.vue"
import FooterVue from "./components/footer.vue"
</script>

<template>
  <header>
    <NavBarVue></NavBarVue>
  </header>
    <MainVue id="Main"></MainVue>
    <PresentationVue id="Presentation"></PresentationVue>
    <TeamVue id="Team"></TeamVue>
    <ContactVue id="Contact"></ContactVue>
    <FooterVue></FooterVue>
</template>

<style>
body {
  min-height:100vh;
  margin: 0;
  padding: 0;
  font-family: poppins; 
}

header {
  background: none;
}

img{
    height: 100%;
    width: 100%;
    object-fit: cover;
}


</style>
