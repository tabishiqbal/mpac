<template>
  <div>

    <div class="w-full lg:max-w-sm mb-10 rounded overflow-hidden shadow-md hover:shadow-lg cursor-pointer relative">
      <img class="w-full" :src="imageUrl" alt="Sunset in the mountains">
      <span class="p-2 absolute pin-t pin-r text-xl" >
        <font-awesome-icon :icon="{ prefix: 'fas', iconName: 'heart' }" class="cursor-pointer text-white hover:text-red" />
      </span>
      <div class="px-6 py-4 border-b">
        <div class="uppercase lg:text-sm text-xs text-grey-darker leading-loose">Detached House - 5Y Old</div>
        <div class="font-bold lg:text-3xl text-base mb-2 ">$750,000</div>
        <p class="text-grey-dark text-sm flex flex-col leading-normal">
          <span>742 Evergreen Terrace</span>
          <span>Toronto, ON L1V 1A1</span>
        </p>
      </div>

      <div class="px-3 py-4">
        <div class="flex -mx-2 text-xs text-grey-darker">
          <div class="w-1/3 px-2">
            <font-awesome-icon :icon="{ prefix: 'fas', iconName: 'bed' }" />
            <span>2bd</span>
          </div>
          <div class="w-1/3 px-2">
            <font-awesome-icon :icon="{ prefix: 'fas', iconName: 'bath' }" />
            <span>2ba</span>
          </div>
          <div class="w-1/3 px-2">
            <span>1200 sqft</span>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  props: ['imageUrl'],

}
</script>
