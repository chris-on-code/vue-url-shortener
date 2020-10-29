<template>
  <div class="app min-h-screen justify-center items-center p-32">
    <!-- header -->
    <div class="rounded-lg p-6 text-center">
      <h1 class="font-bold text-6xl text-white">
        Shorten Your URL
      </h1>
    </div>

    <!-- form -->
    <div class="mt-12 max-w-3xl mx-auto">
      <form action="">
        <input
          type="text"
          class="w-full bg-transparent border-4 border-green-600 rounded-full p-6 mb-8 text-2xl"
          placeholder="https://shorten-this-url.com"
        />
        <div class="text-right">
          <button
            class="py-6 px-10 bg-green-500 text-green-200 rounded-full text-2xl"
          >
            Shorten
          </button>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
.app {
  background: #000b48;
}
</style>
