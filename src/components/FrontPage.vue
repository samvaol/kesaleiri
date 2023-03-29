<template>
  <div class="frontpage-page">
    <h1 class="vaaleansininen big-heading">FUTURA 2023!</h1>
    <p>Here's some text to introduce the website.</p>
  </div>
</template>

<script>
export default {
  name: "FrontPage",
};
</script>

<style scoped>
.frontpage-page {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.vaaleansininen {
  color: var(--vaaleansininen);
}

.big-heading {
  font-size: 4rem;
}
</style>

  
<link rel="stylesheet" href="../assets/main.css">