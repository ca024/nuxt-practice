<template>
    <div class="mx-auto mt-4 max-w-7xl space-y-4 px-4 xs:px-8 sm:px-10 lg:px-16 pb-16 w-3/5">
    <div class="mt-32 flex">
      <!--Car Sidebar-->
      <CarSideBar />
      <!--Car Sidebar-->

      <!--Car Cards-->
      <div>
      <NuxtPage />
    </div>
      <!--Car Cards-->
    </div>
    <!--Cars page-->
  </div>
</template>

<script setup>
const route = useRoute()
useHead({
  title: `Cars in ${route.params.city}`
})

</script>