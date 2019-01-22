<template>
  <div>
    <section class="py-6 container mx-auto max-w-xl">
      <h1 class="text-heading-black mb-6 text-2xl">New Listings</h1>
    
      <div class="flex -mx-2">
        <div class="w-1/3 px-2">
          <card :imageUrl="image7"></card>
        </div>
        <div class="w-1/3 px-2">
          <card :imageUrl="image8"></card>
        </div>
        <div class="w-1/3 px-2">
          <card :imageUrl="image9"></card>
        </div>
        
      </div>
    </section>
  </div>
</template>

<script>
import Card from '~/components/Card.vue'
export default {
  components: {
    Card,
  },

  data() {
    return {
      image7: 'https://images.unsplash.com/photo-1510627489930-0c1b0bfb6785?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80',
      image8: 'https://images.unsplash.com/photo-1430285561322-7808604715df?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80',
      image9: 'https://images.unsplash.com/photo-1459535653751-d571815e906b?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1349&q=80',
    }
  }

}
</script>