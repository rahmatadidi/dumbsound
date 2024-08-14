<script lang="ts">
export default {
  name: "Card",
};
</script>

<template>
  <div class="card bg-zinc-950 w-52 shadow-xl">
    <figure class="px-3 pt-3 h-52">
      <img
        src="https://www.microdotboutique.com/cdn/shop/products/Couple.jpg?v=1652452551"
        alt="Shoes"
        class="rounded-xl h-full"
      />
    </figure>
    <div class="px-3 pt-3 flex justify-between">
      <h2 class="font-bold">Stand By Me</h2>
      <p>1997</p>
    </div>
    <p class="px-3 py-3">Oasis</p>
  </div>
</template>
