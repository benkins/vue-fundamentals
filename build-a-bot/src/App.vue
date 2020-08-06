<template>
  <div id="app">
    <NavBar />
    <main>
      <RobotBuilder />
    </main>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue';
import RobotBuilder from './build/RobotBuilder.vue';

export default {
  name: 'App',
  components: {
    RobotBuilder,
    NavBar,
  },
};
</script>
<style>
body {
  background: linear-gradient(to bottom, #555, #999);
  background-attachment: fixed;
}
</style>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
main {
  margin: 0 auto;
  padding: -30px;
  background-color: white;
  width: 800px;
  min-height: 300px;
}
</style>
