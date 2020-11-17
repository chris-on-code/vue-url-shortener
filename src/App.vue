<template>
  <div
    class="bg-gradient-to-br from-purple-700 to-purple-900 min-h-screen flex justify-center items-center pb-32"
  >
    <div class="max-w-4xl mx-auto">
      <!-- header -->
      <div class="rounded-lg text-center">
        <h1
          class="font-bold text-6xl text-white italic uppercase tracking-widest"
        >
          Shorten Your URL
        </h1>
      </div>

      <!-- form -->
      <form
        action=""
        class="flex items-center bg-black bg-opacity-25 rounded py-3 pr-4 pl-6"
      >
        <input
          type="text"
          class="w-full bg-transparent text-2xl outline-none"
          placeholder="https://shorten-this-url.com"
        />
        <div class="text-right">
          <button class="py-3 px-10 bg-purple-100 rounded text-xl">
            Shorten
          </button>
        </div>
      </form>
    </div>
  </div>
</template>
