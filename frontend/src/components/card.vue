<template>
  <div class="flex flex-col bg-white shadow blue-hover"
    style="width: 360px; border-radius: 1px;">
    <img src="https://images.pexels.com/photos/442559/pexels-photo-442559.jpeg?auto=compress&cs=tinysrgb"
      alt="Man with backpack" class="block w-full">
    <div class="px-6 py-6">
      <p class="mb-0 text-moss text-sm uppercase mb-4 tracking-widest">
        <router-link to="/tagged/travel">Travel</router-link>
      </p>
      <h1 class="font-medium text-padua-100 text-2xl mt-0 mb-4" style="line-height: 1.25;">
        <router-link to="/post/something">Planning your final summer trip</router-link>
      </h1>
      <p class="mb-1 text-gray-500">
        Summer is coming to a close just around the corner. But it's not too late to squeeze in another weekend trip
        &hellip;
      </p>
    </div>
  </div>
</template>

<script>
export default {

}

</script>

<style scoped>
.blue-hover {
  transition: all 0.25s ease-in;
  border-bottom: 5px solid transparent;
}
.blue-hover:hover {
  transform: translateY(-5px);
  border: none;
  border-bottom: 5px solid theme('colors.padua.400');
}
</style>
