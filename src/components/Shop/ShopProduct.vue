<template>
  <div class="product d-flex flex-col">
    <div class="product-image">
      <!-- <img
        src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTpQZ_PcmsDhN4emM1aZftV42wch2lSS0-hvw&s"
      /> -->
    </div>
    <div class="p-10 d-flex flex-col">
      <h4>Macbook Pro</h4>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
        labore et dolore magna aliqua.
      </p>
      <div class="d-flex flex-row align-items-c">
        <span class="flex-fill"> Prix: 2000€ </span>
        <button class="btn btn-primary">Ajouter au panier</button>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup></script>

<style lang="scss" scoped>
.product {
  background-color: white;
  border: var(--border);
  border-radius: var(--border-radius);
  &-image {
    border-top-right-radius: var(--border-radius);
    border-top-left-radius: var(--border-radius);
    background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTpQZ_PcmsDhN4emM1aZftV42wch2lSS0-hvw&s');
    height: 250px;
    background-position: center;
    background-size: cover;
  }
}
</style>
