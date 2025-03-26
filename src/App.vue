<script setup></script>

<template>
  <div
    ref="dark"
    class="h-full p-4 bg-amber-50 dark:bg-gradient-to-br from-emerald-950 to-indigo-950"
  >
    <div
      @click="$refs.dark.classList.toggle('dark')"
      class="flex w-full text-[8px] sm:text-base dark:text-white"
    >
      <button class="cursor-pointer">Promijeni temu</button>
    </div>
    <div class="flex flex-col justify-center items-center gap-3">
      <p class="text-xl xl:text-6xl sm:text-4xl dark:text-white">
        Pozdrav, ja sam
        <span class="text-cyan-400">Bruno Rebić</span>
      </p>

      <div
        class="w-64 xl:w-5xl md:w-2xl sm:w-xl border-2 opacity-75 rounded-full border-zinc-700 bg-zinc-700 dark:bg-white p-0.5"
      ></div>

      <p class="text-lg sm:text-2xl text-cyan-400 dark:text-teal-100/75">
        Moji omiljeni filmovi
      </p>

      <div
        class="flex gap-2 justify-center items-center text-xl xl:text-6xl sm:text-4xl text-zinc-700 text-center"
      >
        <div>
          <div
            class="w-20 h-30 xl:w-80 xl:h-120 sm:w-50 sm:h-70 rounded-md bg-zinc-300 flex justify-center items-center"
          >
            Poster
          </div>
          <div class="dark:text-white text-xs sm:text-2xl">Naslov filma</div>
        </div>

        <div>
          <div
            class="w-20 h-30 xl:w-80 xl:h-120 sm:w-50 sm:h-70 rounded-md bg-zinc-300 flex justify-center items-center"
          >
            Poster
          </div>
          <div class="dark:text-white text-xs sm:text-2xl">Naslov filma</div>
        </div>

        <div>
          <div
            class="w-20 h-30 xl:w-80 xl:h-120 sm:w-50 sm:h-70 rounded-md bg-zinc-300 flex justify-center items-center"
          >
            Poster
          </div>
          <div class="dark:text-white text-xs sm:text-2xl">Naslov filma</div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
