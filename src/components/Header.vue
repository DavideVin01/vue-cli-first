<template>
  <header class="shadow">
    <h1 id="title" class="scale-up-center">
      La mia prima app con <span id="text-green">Vue CLI!</span>
    </h1>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style>
header {
  background-color: #43b885;
}

#title {
  color: #36495e;
}

#text-green {
  color: #98ffd2;
}
</style>