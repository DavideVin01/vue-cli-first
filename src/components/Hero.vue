<template>
  <main>
    <img id="jumbotron" src="@/assets/Jumbotron.png" alt="Jumbotron" />
  </main>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style>
#jumbotron {
  max-width: 100%;
  box-shadow: 0 2px 5px 0 black;
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
</style>