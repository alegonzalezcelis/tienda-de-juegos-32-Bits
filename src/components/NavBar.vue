<template>
  <div
    class="text-sm font-medium text-center text-gray-500 border-b border-gray-200 dark:text-gray-400 dark:border-gray-700 mb-8"
  >
    <ul class="flex flex-wrap -mb-px">
      <li class="mr-2">
        <router-link
          to="/"
          class="inline-block p-4 rounded-t-lg border-b-2 border-transparent hover:text-blue-600 hover:border-blue-600"
          >Home</router-link
        >
      </li>
      <li class="mr-2">
        <router-link
          to="/juegos"
          class="inline-block p-4 rounded-t-lg border-b-2 border-transparent hover:text-blue-600 hover:border-blue-600"
          >Juegos</router-link
        >
      </li>
    </ul>
  </div>
</template>

<script>
export default {}
</script>

<style></style>
