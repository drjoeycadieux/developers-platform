<template>
  <div id="app">
    <Header />
    <router-view />

    <FooterPage />
    <hr />
    <FooterMedia />
  </div>
</template>

<script>
import Header from "./components/Header";
import FooterPage from "./components/FooterPage";
import FooterMedia from "./components/FooterMedia";

export default {
  name: "App",
  components: {
    Header,
    FooterPage,
    FooterMedia,
  },
};
</script>