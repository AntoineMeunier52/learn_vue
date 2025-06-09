<template>
  <header class="d-flex flex-row align-items-c">
    <a href="#" class="px-20 d-flex flex-rows align-items-c">
      <img src="../assets/logo.svg" />
      <span class="logo">Meunco</span>
    </a>
    <ul class="px-20 d-flex flex-row flex-fill">
      <li class="mr-20">
        <a href="#">Boutique</a>
      </li>
      <li>
        <a href="#">Admin</a>
      </li>
    </ul>
    <ul class="px-20 d-flex flex-row">
      <li class="mr-20">
        <a href="#">Inscription</a>
      </li>
      <li>
        <a href="#">Connexion</a>
      </li>
    </ul>
  </header>
</template>

<script lang="ts" setup></script>

<style lang="scss" scoped>
header {
  background-color: var(--primary-1);
  a {
    color: var(--text-primary-color);
    img {
      width: 20px;
      margin-right: 5px;
    }
    .logo {
      font-weight: 700;
      font-size: 20px;
    }
  }
}
</style>
