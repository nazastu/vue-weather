<template>
  <div class="app">
    <main>
      <div class="search-box">
        <input type="text" class="search-bar" placeholder="Search..." />
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      api_key: "9f5340571f4c6c4f374064135c1a72f9",
    };
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "montserrat", sans-serif;
}

#app {
  background-image: url();
}
</style>
