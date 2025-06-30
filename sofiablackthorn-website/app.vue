<template>
  <div>
    <section class="main-section">
      <div class="header-container">
        <Header />
      </div>
    </section>
  </div>
</template>

<script lang="ts" setup>
import "./assets/font.css";
import "./assets/color.css";
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background: #1f1d1d;
  background: linear-gradient(
    90deg,
    rgba(31, 29, 29, 1) 0%,
    rgba(63, 27, 194, 1) 100%
  );
}

.main-section {
  width: 100%;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}

.header-container {
  max-width: 1200px;
  margin: 0 auto;
}
</style>
