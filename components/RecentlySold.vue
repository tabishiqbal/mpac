<template>
  <div>
    <section class="py-6 container mx-auto max-w-xl">
      <h1 class="text-heading-black mb-6 text-2xl">Recently Sold</h1>
    
      <div class="flex -mx-2">
        <div class="w-1/3 px-2">
          <card :imageUrl="image4"></card>
        </div>
        <div class="w-1/3 px-2">
          <card :imageUrl="image5"></card>
        </div>
        <div class="w-1/3 px-2">
          <card :imageUrl="image6"></card>
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
      image4: 'https://images.unsplash.com/photo-1512917774080-9991f1c4c750?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60',
      image5: 'https://images.unsplash.com/photo-1485996463739-9cb09adbe6c5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80',
      image6: 'https://images.unsplash.com/photo-1530745379816-bdc7e6f1356c?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80',
    }
  }

}
</script>
