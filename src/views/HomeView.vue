<template>
  <div class="custom-gradient py-2">
    <div class="container mx-auto flex items-center justify-evenly">
      <img class="logo" src="../assets/logomuhammadiyahorid-1-e1707738991754.png" alt="">
      <div class="flex items-center gap-4 font-semibold">
        <router-link to="/" class="block text-sm text-white">ORGANISASI</router-link>
        <router-link to="/about" class="block text-sm text-white">DIREKTORI</router-link>
        <router-link to="/contact" class="block text-sm text-white">GALERI</router-link>
        <router-link to="/contact" class="block text-sm text-white">KAJIAN</router-link>
        <router-link to="/contact" class="block text-sm text-white">ARTIKEL</router-link>
        <router-link to="/contact" class="block text-sm text-white">BERITA</router-link>
      </div>
      <SearchIcon class="h-5 w-5 text-white" />
    </div>
  </div>
</template>

<script>
import { SearchIcon } from "@heroicons/vue/solid"

export default {
  components: {
    SearchIcon
  }
}
</script>

<style scoped>
.logo {
  width: 270px;
  height: auto;
}

.custom-gradient {
  background: linear-gradient(to right, #348dd6 35%, #4299E1, #68D391);
}
</style>