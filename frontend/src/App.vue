<template>
  <Header />

  <RouterView />
  <Footer />
</template>

<script>
import Home from "./components/Home.vue";
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";

export default {
  components: {
    Home,
    Header,
    Footer,
  },
};
</script>
