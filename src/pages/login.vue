<script setup></script>

<template>
  <div
    class="flex flex-col items-center justify-center space-y-12  min-h-screen-nonav"
  >
    <div
      class="flex items-center justify-center overflow-hidden bg-gray-200 rounded-lg shadow-2xl "
    >
      <img class="h-64" src="../assets/bglogin.png" alt="Hello BG" />
      <form class="flex flex-col p-4 space-y-4">
        <input
          type="text"
          class="p-2 border-2 rounded-lg"
          placeholder="Username"
        />
        <input
          type="password"
          class="p-2 border-2 rounded-lg"
          placeholder="Password"
        />
        <button
          type="submit"
          class="py-2 text-indigo-200 bg-indigo-600 rounded-lg"
        >
          Login
        </button>
      </form>
    </div>
  </div>
</template>
