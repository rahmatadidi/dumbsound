<script lang="ts">
import Card from "../components/card.vue";
export default {
  name: "Home",
  components: { Card },
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
        <div class="flex h-1/2">
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
          <div
            class="flex flex-col justify-center align-center text-white text-xl w-1/3"
          >
            <div class="m-auto flex flex-col gap-6">
              <h1 class="text-center text-4xl font-bold">
                Connect On DumbSound
              </h1>
              <h1 class="text-center">
                Discovery, Stream, and share a contanly expanding mix of music
                from emerging and major artists around the world.
              </h1>
            </div>
          </div>
          <div class="flex gap-4 w-1/3 justify-end">
            <button class="btn btn-outline w-[100px] h-[30px] text-white">
              Login
            </button>
            <button class="btn btn-error w-[100px] h-[30px] text-white">
              Register
            </button>
          </div>
        </div>
        <div class="text-center text-red-500 text-xl font-bold mt-20">
          <h1>Dengarkan Dan Rasakan</h1>
        </div>
        <div class="pt-20 pl-2 mb-4 flex flex-wrap justify-center gap-4">
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
        </div>
      </div>
    </div>
  </div>
</template>
