<template>
  <div id="app">
    <Header/>
    <Body/>
    <Footer/>
  </div>
</template>
<script>
import Header from "./components/header";
import Body from "./components/body";
import Footer from "./components/footer";

export default {
  name: "App",
  components: { Header, Body, Footer }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
