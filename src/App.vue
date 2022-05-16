<template>
  <div id="app">
    <MyTitle />
  </div>
</template>

<script>
import MyTitle from "./components/MyTitle.vue";

export default {
  name: "App",
  components: {
    MyTitle,
  },
};
</script>

<style>
html {
  background-image: url(https://p4.wallpaperbetter.com/wallpaper/1001/338/527/5bd24c44cbdf7-wallpaper-preview.jpg);
  background-size: cover;
}
#app {
  height: 80vh;
  width: 80vw;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 0 auto;
  background-size: cover;
}

h1 {
  background-color: #18171e;
  color: white;
  border: #87aa37 solid 10px;
  border-radius: 10px;
  padding: 40px;
}
.bg-image {
  object-fit: contain;
  width: 100%;
}
</style>
