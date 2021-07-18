<template>
<HeaderComponent></HeaderComponent>
<MenuComponent></MenuComponent>
<PartiesComponent></PartiesComponent>
<WatchComponent></WatchComponent>
<HomeComponent></HomeComponent>
<FooterComponent></FooterComponent>

</template>



<script>
import HeaderComponent from "./components/shared/Header.vue";
import MenuComponent from "./components/shared/Menu.vue";
import FooterComponent from "./components/shared/Footer.vue";
import PartiesComponent from "./components/pages/Parties.vue";
import WatchComponent from "./components/pages/Watch.vue";
import HomeComponent from "./components/pages/Home.vue";


export default {
  components: {
    HeaderComponent,
    MenuComponent,
    FooterComponent,
    PartiesComponent,
    WatchComponent,
    HomeComponent,
  },
  setup() {
    
    return {
     
    };
  },
}
</script>



<style>


</style>
