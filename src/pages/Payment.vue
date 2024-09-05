<script setup lang="ts">
import AvatarDropdown from "../components/AvatarDropDown.vue";
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
          <AvatarDropdown />
        </div>
        <div class="flex justify-center -mt-32 align-center">
          <div class="flex flex-col w-1/2">
            <h1 class="text-center text-4xl font-bold text-white pb-4">
              Premium
            </h1>
            <h2 class="text-white text-center">
              Bayar sekarang dan nikmati streaming music yang kekinian dari
              DUMB<span class="text-red-500">SOUND</span>
            </h2>
            <h2 class="text-white text-center mb-8">
              DUMB<span class="text-red-500">SOUND</span> : 0981312323
            </h2>
            <input
              type="text"
              placeholder="Input your Acount number"
              class="input input-bordered w-full max-w-xs m-auto border-white text-white"
            />
            <label
              class="cursor-pointer flex items-center space-x-2 w-full max-w-xs m-auto border rounded-lg p-4 h-11 border-white mt-4"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 16 16"
                fill="currentColor"
                class="size-4 text-red-500"
              >
                <path
                  fill-rule="evenodd"
                  d="M11.914 4.086a2 2 0 0 0-2.828 0l-5 5a2 2 0 1 0 2.828 2.828l.556-.555a.75.75 0 0 1 1.06 1.06l-.555.556a3.5 3.5 0 0 1-4.95-4.95l5-5a3.5 3.5 0 0 1 4.95 4.95l-1.972 1.972a2.125 2.125 0 0 1-3.006-3.005L9.97 4.97a.75.75 0 1 1 1.06 1.06L9.058 8.003a.625.625 0 0 0 .884.883l1.972-1.972a2 2 0 0 0 0-2.828Z"
                  clip-rule="evenodd"
                />
              </svg>

              <span class="text-red-500">Upload File</span>
              <input
                type="file"
                class="hidden"
              />
            </label>
            <button
              class="btn btn-error text-white max-w-xs w-full m-auto mt-4"
            >
              Send
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
