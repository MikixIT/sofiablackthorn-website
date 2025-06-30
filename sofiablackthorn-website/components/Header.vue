<template>
  <div class="header font-poppins-regular">
    <a href="#">Social Media</a>
    <a href="#">For Collaborations</a>
    <span></span>
    <a class="btn" href="#">Guarda Ora</a>
  </div>
</template>

<script lang="ts" setup></script>

<style>
.header {
  display: flex;
  gap: 30px;
  align-items: center;
  padding: 10px 20px;
}
.header a {
  color: var(--color-text);
  text-decoration: none;
  font-size: 1.2em;
}
.header a.btn {
  background-color: var(--color-violet);
  color: var(--color-text);
  padding: 16px 20px;
  border-radius: 5px;
}
</style>
