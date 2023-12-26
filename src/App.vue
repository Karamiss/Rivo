
<template>
  <app-header class="header-outside-app" />
  <main-preview/>
  <about-us/>
  <app-footer />
</template>

<script>
import AppHeader from "@/components/common/Header";
import MainPreview from "@/pages/main/agency-rivo/Preview";
import AboutUs from "@/pages/main/agency-rivo/About-us";
import AppFooter from "@/components/common/Footer";


export default {
  name: "App",
  components: {
    AppHeader,
    MainPreview,
    AboutUs,
    AppFooter,
  },
};
</script>

<style  lang="scss">
#app {
  
  color: #1A1A1A;
  font-family: Arial;
  // padding: 2% 255px

}
body {
  background: #F3F3F5;
  margin: 0;
  padding: 0; 
 
}
.header-outside-app {
  box-sizing: border-box;
  // padding: 2% 72px;
  padding: clamp (15px, 3vw, 72px)
}
#app  {
  margin: 12px 0;
}
@media screen and (max-width: 640px) {
  #app  {
    margin: 12px 0;
  }
}
@media screen and (min-width: 641px) and (max-width: 1440px) {
  #app  {
    margin: 12px 5%;
  }
}
@media screen and (min-width: 1441px) and (max-width: 2560px) {
  #app  {
    margin: 12px 10%;
  }
}
@media screen and (min-width: 2561px) {
  #app  {
    margin: 12px 15%;
  }
}
</style>

