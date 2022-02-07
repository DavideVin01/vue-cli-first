<template>
  <div id="app" class="shadow">
    <Header />
    <Hero />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Hero from "@/components/Hero.vue";
export default {
  name: "App",
  components: {
    Header,
    Hero,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: sans-serif;
  text-align: center;
  margin: 0 auto;
  background-image: url("assets/background.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  height: 100vh;
}

.scale-up-center {
  animation: scale-up-center 0.4s cubic-bezier(0.39, 0.575, 0.565, 1) both;
}

@keyframes scale-up-center {
  0% {
    transform: scale(0.5);
  }
  100% {
    transform: scale(1);
  }
}

.shadow {
  box-shadow: 0 5px 15px 0px black;
}
</style>