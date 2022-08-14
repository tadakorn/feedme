<template>
  <div class="container">
    <header>
      <nav class="navbar navbar-light bg-light">
        <div class="container">
          <a class="navbar-brand" href="#">
            <img
              src="./assets/logo.png"
              alt=""
              width="30"
              height="24"
            />
          </a>
        </div>
      </nav>
    </header>

    <RouterView />
  </div>
</template>

<script>
import { RouterLink, RouterView } from "vue-router";

export default {
  components: {
    RouterLink,
    RouterView,
  }
}
</script>

<style scoped>
</style>
