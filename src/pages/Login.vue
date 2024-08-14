<script lang="ts">
export default {
  name: "Login",
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
        class="absolute inset-0 bg-gradient-to-b from-transparent via-black p-5 flex justify-center align-center"
      >
        <div class="card lg:card-side bg-base-100 shadow-xl h-1/2 w-1/2 m-auto">
          <figure class="w-1/2">
            <img
              src="https://img.daisyui.com/images/stock/photo-1494232410401-ad00d5433cfa.webp"
              alt="Album"
              class="w-full h-full"
            />
          </figure>
          <div class="flex flex-col gap-6 p-10">
            <h2 class="font-bold text-white text-4xl">Login</h2>
            <label class="input input-bordered flex items-center gap-2">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 16 16"
                fill="currentColor"
                class="h-4 w-4 opacity-70"
              >
                <path
                  d="M2.5 3A1.5 1.5 0 0 0 1 4.5v.793c.026.009.051.02.076.032L7.674 8.51c.206.1.446.1.652 0l6.598-3.185A.755.755 0 0 1 15 5.293V4.5A1.5 1.5 0 0 0 13.5 3h-11Z"
                />
                <path
                  d="M15 6.954 8.978 9.86a2.25 2.25 0 0 1-1.956 0L1 6.954V11.5A1.5 1.5 0 0 0 2.5 13h11a1.5 1.5 0 0 0 1.5-1.5V6.954Z"
                />
              </svg>
              <input
                type="text"
                class="grow"
                placeholder="Email"
              />
            </label>
            <label class="input input-bordered flex items-center gap-2">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 16 16"
                fill="currentColor"
                class="h-4 w-4 opacity-70"
              >
                <path
                  fill-rule="evenodd"
                  d="M14 6a4 4 0 0 1-4.899 3.899l-1.955 1.955a.5.5 0 0 1-.353.146H5v1.5a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1-.5-.5v-2.293a.5.5 0 0 1 .146-.353l3.955-3.955A4 4 0 1 1 14 6Zm-4-2a.75.75 0 0 0 0 1.5.5.5 0 0 1 .5.5.75.75 0 0 0 1.5 0 2 2 0 0 0-2-2Z"
                  clip-rule="evenodd"
                />
              </svg>
              <input
                type="password"
                class="grow"
                placeholder="Password"
              />
            </label>
            <div class="card-actions justify-end">
              <button class="btn btn-primary w-full">Login</button>
            </div>
            <p class="">
              Don't have an account? Klik
              <a
                class="font-bold"
                href="#"
                >Here</a
              >
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
