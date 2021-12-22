<template>
  <h1 class="main_title">Team Sign up</h1>
  <NavBar msg="Welcome to Your Vue.js App"/>
</template>

<script>
import NavBar from './components/NavBar.vue'

export default {
  name: 'App',
  components: {
    NavBar
  }
}
</script>

<style>
#app {
  height: 821px;
  width: 680px;

  border-radius: 20px;
  padding: 15px 35px;

  display: flex;
  flex-direction: column;
  align-self: center;
  flex: 1;

  font-family: 'Roboto', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;

  color: #000000;
  background: #ffffff;
}

.main_title {
  font-size: 36px;
  font-weight: normal;
  line-height: 1.8;
  letter-spacing: -1.5px;
  text-align: left;
}
</style>


// import Vue from "vue";
// import VueRouter from "vue-router";

// Vue.use(VueRouter);

// import Personal from "./components/Personal.vue";
// import Social from "./components/Social.vue";
// import Certifications from "./components/Certifications.vue";
// import Resume from './components/Resume.vue'

// const router = new VueRouter({
//   mode: "history",
//   base: __dirname,
//   routes: [
//     { path: "/", component: Personal },
//     { path: "/social", component: Social },
//     { path: "/certifications", component: Certifications },
//     { path: "/resume", component: Resume }
//   ],
// });

// new Vue({
//   router,
//   template: `
//     <div>
//     </div>
//   `,
// }).$mount("#app");