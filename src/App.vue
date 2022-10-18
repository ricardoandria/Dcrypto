<template>
  <div class="container">
    <NavBar />
    <Heros />
    <Trading />
    <Account />
    <Time />
    <Analyse />
    <Access />
    <Connect />
    <Ethereal />
    <Footer />
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import Heros from "./components/Heros.vue";
import Trading from "./components/Trading.vue";
import Account from "./components/Account.vue";
import Time from "./components/Time.vue";
import Analyse from "./components/Analyse.vue";
import Access from "./components/Access.vue";
import Connect from "./components/connecte.vue";
import Ethereal from "./components/Ethereal.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  data() {
    return {};
  },
  components: {
    NavBar,
    Heros,
    Trading,
    Account,
    Time,
    Analyse,
    Access,
    Connect,
    Ethereal,
    Footer,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Montserrat", sans-serif;
  scroll-behavior: smooth;
}

ul li {
  list-style-type: none;
}
ul li a {
  text-decoration: none;
  color: inherit;
  color: white;
}
button {
  padding: 10px 19px;
  border-radius: 32px;
  background: #263aa5;
  box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.06);
  border-radius: 30px;
  border: none;
  color: white;
  font-size: 1rem;
}
h1,
h2,
h3,
h4,
h5,
h6 {
  font-weight: 600;
}
</style>
