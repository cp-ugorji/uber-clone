<template>
  <div id="Home" class="flex flex-col h-screen">
    <div class="md mb-auto">
      <div class="grid grid-cols-2 gap-3 my-3">
        <ServiceSelectLarge text="Ride" imageWidth="74" image="ride" />
        <ServiceSelectLarge
          text="Food"
          imageWidth="72"
          image="food"
          :promo="true"
        />
      </div>
    </div>
  </div>
</template>

<script setup>
// @ is an alias to /src
import ServiceSelectLarge from "@/components/ServiceSelectLarge";
</script>
