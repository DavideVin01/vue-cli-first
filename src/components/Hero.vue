<template>
  <main>
    <img
      id="jumbotron"
      class="scale-up-center shadow"
      src="@/assets/Jumbotron.png"
      alt="Jumbotron"
    />
  </main>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style>
#jumbotron {
  margin-top: 10px;
  width: 1000px;
  animation: scale-up-center 0.4s cubic-bezier(0.39, 0.575, 0.565, 1) both;
}
</style>