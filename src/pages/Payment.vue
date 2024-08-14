<script lang="ts">
export default {
  name: "Payment",
};
</script>
<template>
  <div class="w-full h-screen">
    <div
      class="bg-cover bg-center h-1/2"
      style="
        background-image: url(https://images.pexels.com/photos/1105666/pexels-photo-1105666.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2);
      "
    >
      <div
        class="absolute inset-0 bg-gradient-to-b from-transparent via-black p-5"
      >
        <div class="flex h-1/2 justify-between">
          <div class="flex gap-2 h-10 w-1/3">
            <img
              src="../assets/image/image-dumbsound.png"
              alt="logo"
              class="w-10 h-10"
            />
            <h1 class="flex items-center">
              Dumb<span class="text-red-500">Sound</span>
            </h1>
          </div>
          <div class="avatar h-12 w-12">
            <div
              class="ring-white ring-offset-base-100 w-24 rounded-full ring ring-offset-2"
            >
              <img
                src="https://img.daisyui.com/images/stock/photo-1534528741775-53994a69daeb.webp"
              />
            </div>
          </div>
        </div>
        <div>
          <h1 class="text-center text-4xl font-bold text-white">Premium</h1>
          <h2 class="text-center text-white">
            Bayar sekarang dan nikmati streaming music yang kekinian dari
          </h2>
        </div>
      </div>
    </div>
  </div>
</template>
