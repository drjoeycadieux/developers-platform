<template>
  <div id="app">
    <Header />
    <router-view />

    <FooterPage />
  </div>
</template>

<script>
import Header from "./components/Header";
import FooterPage from "./components/FooterPage";

export default {
  name: "App",
  components: {
    Header,
    FooterPage,
  },
};
</script>