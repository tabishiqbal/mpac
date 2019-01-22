<template>
  <div>
    <div class="mb-8">
      <navbar></navbar>
      <hero></hero>
    </div>

    <div class="container mx-auto lg:max-w-xl md:max-w-sm">
      <safe-neighbourhoods></safe-neighbourhoods>
      <new-listings></new-listings>
      <recently-sold></recently-sold>
    </div>
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue';
import Hero from '~/components/Hero.vue';
import SafeNeighbourhoods from '~/components/SafeNeighbourhoods.vue';
import NewListings from '~/components/NewListings.vue';
import RecentlySold from '~/components/RecentlySold.vue';

export default {
  components: {
    Hero,
    Navbar,
    SafeNeighbourhoods,
    NewListings,
    RecentlySold,
  },
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.explore-homes {
  height: 300px;
  background: url(https://images.unsplash.com/photo-1519643225200-94e79e383724?ixlib=rb-1.2.1&auto=format&fit=crop&w=1355&q=80) center center no-repeat;
}
</style>
