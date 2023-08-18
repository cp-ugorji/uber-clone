<template>
  <div id="Home" class="flex flex-col h-screen">
    <div class="md mb-auto">
      <div class="my-20">
        <img width="150" src="img/uber/uber2.svg" />
      </div>

      <div class="grid grid-cols-2 gap-3 my-3">
        <ServiceSelectLarge text="Ride" imageWidth="74" image="ride" />
        <ServiceSelectLarge
          text="Food"
          imageWidth="72"
          image="food"
          :promo="true"
        />
      </div>

      <div class="grid grid-cols-4 gap-3 my-3">
        <ServiceSelectSmall text="2 Wheels" image="2wheels" />
        <ServiceSelectSmall text="Transit" image="transit" />
        <ServiceSelectSmall text="Reserve" image="reserve" />
        <ServiceSelectSmall text="Travel" image="travel" />
      </div>
    </div>
  </div>
</template>

<script setup>
// @ is an alias to /src
import ServiceSelectLarge from "@/components/ServiceSelectLarge";
import ServiceSelectSmall from "@/components/ServiceSelectSmall";
</script>
