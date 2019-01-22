<template>
  <div>
    <section class="py-6 container mx-auto max-w-xl">
        <h1 class="text-heading-black mb-6 text-2xl">Safe Neighbourhoods</h1>
      
        <div class="flex flex-col lg:flex-row -mx-2">
          <div class="lg:w-1/3 w-full px-2">
            <card :imageUrl="image1"></card>
          </div>
          <div class="lg:w-1/3 w-full px-2">
            <card :imageUrl="image2"></card>
          </div>
          <div class="lg:w-1/3 w-full px-2">
            <card :imageUrl="image3"></card>
          </div>
        </div>
      </section>
  </div>
</template>

<script>
import Card from '~/components/Card.vue';
export default {
  components: {
    Card,
  },

  data() {
    return {
      image1: 'https://images.unsplash.com/photo-1475855581690-80accde3ae2b?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60',
      image2: 'https://images.unsplash.com/photo-1480074568708-e7b720bb3f09?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60',
      image3: 'https://images.unsplash.com/photo-1513584684374-8bab748fbf90?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60',
    }
  }
  
}
</script>
