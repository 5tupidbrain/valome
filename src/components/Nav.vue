<template>
  <nav
    class="bg-slate-800 flex md:flex-col space-y-2 items-center flex-start md:w-14 md:py-4"
  >
    <div class="grid place-items-center">
      <router-link :to="{ name: 'Home' }"> VMe </router-link>
    </div>
    <div>
      <button id="Menu" class="text-red-400">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-6 w-6"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          stroke-width="2"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
          />
        </svg>
      </button>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style></style>
