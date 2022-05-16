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
  background-color: #18181e;
}
#app {
  height: 80vh;
  width: 80vw;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 0 auto;
}

h1 {
  background-color: #18181e;
  color: white;
  border: #87aa37 solid 20px;
  border-radius: 10px;
  padding: 80px;
}
</style>
