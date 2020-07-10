<template>
  <header class="text-gray-700 body-font">
    <div class="container mx-auto flex flex-wrap p-5 flex-row items-center justify-between md:justify-start">
      <router-link to="/" tag="span" class="cursor-pointer">
        <img src="@/assets/img/burger-icon.png" alt="burger" class="w-12" />
      </router-link>
      <router-link
        to="/"
        tag="span"
        class="ml-3 text-xl cursor-pointer hidden md:block"
      >The Corner Burger</router-link>
      <div class="hidden md:ml-auto md:flex flex-wrap items-center text-base justify-center">
        <nav class="">
          <a class="mr-5 hover:text-gray-900">Menú</a>
          <a class="mr-5 hover:text-gray-900">Compromiso</a>
          <a class="mr-5 hover:text-gray-900">Conócenos</a>
          <a class="mr-5 hover:text-gray-900">Sugerencias</a>
        </nav>
        <button
          class="inline-flex items-center bg-gray-200 border-0 py-1 px-3 focus:outline-none hover:bg-gray-300 rounded text-base"
        >
          <users-icon class="w-5 h-5 mr-2"></users-icon>
          <span>Login</span>
        </button>
      </div>
      <div class="md:hidden">
        <menu-icon></menu-icon>
      </div>
    </div>
  </header>
</template>

<script>
import { UsersIcon } from "vue-feather-icons"
import { MenuIcon } from 'vue-feather-icons'

export default {
  components: {
    UsersIcon,
    MenuIcon
  }
};
</script>