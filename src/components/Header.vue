<template>
  <header class="header">
    <div class="logo">
      <img src="../assets/futura.png" alt="Logo">
    </div>
    <Navbar />
  </header>
</template>

<script>
import Navbar from './Navbar.vue'

export default {
  components: {
    Navbar
  }
}
</script>

<style scoped>
.header {
  background-color: var(--partionsininen);
  height: 10%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 10px;
}

.logo {
  height: 12vh;
  max-width: 80px;
  max-height: 70px;
  margin-right: auto; /* Push the logo to the right */
}
</style>

<link rel="stylesheet" href="./assets/main.css">