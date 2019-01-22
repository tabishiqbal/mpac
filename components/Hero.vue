<template>
  <div class="hero-bg">
    <div class="pt-32">
      <div class="mt-6 flex flex-col items-center justify-center w-full h-full">
        <div class="text-white text-5xl font-bold text-center">
          <div>Discover a place</div>
          <div>you'll love to live</div>
        </div>
        <div class="flex justify-center w-full mt-10">
          <div class="absolute lg:w-1/2 w-4/5 justify-center flex ">
            <input type="text" class="block w-full h-12 pl-4 appearance-none focus:outline-none focus:bg-white rounded" placeholder="New York, NY">
            <span class="absolute pin-r pin-t flex text-white p-4 bg-red-light rounded-r"><font-awesome-icon :icon="{ prefix: 'fas', iconName: 'search' }" /></span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>


export default {  
}
</script>


<style scoped>
.hero-bg {
  height: 500px;
  width: 100%;
  background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0) 10%) 0% 0% / cover, url(https://static.trulia-cdn.com/images/homepage/header_background_v3_hd.jpg) center center no-repeat;
  /* background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0) 10%) 0% 0% / cover, url(https://images.unsplash.com/photo-1519643225200-94e79e383724?ixlib=rb-1.2.1&auto=format&fit=crop&w=1355&q=80) center center no-repeat; */
  /* background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0) 10%) 0% 0% / cover, url(https://images.unsplash.com/photo-1489171078254-c3365d6e359f?ixlib=rb-1.2.1&auto=format&fit=crop&w=1489&q=80) center center no-repeat; */
  /* background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0) 10%) 0% 0% / cover, url(https://images.unsplash.com/photo-1473798349978-d18a8c8dbf41?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80) center center no-repeat; */
}
</style>

