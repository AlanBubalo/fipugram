<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <div class="jumbotron">
      <h1 class="display-4">Welcome to Vue</h1>
      <p class="lead">You can login by clicking the "Login" button.</p>
      <hr class="my-4" />
      <p>Or if you don't have an account, sign up.</p>
    </div>
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
};
</script>
