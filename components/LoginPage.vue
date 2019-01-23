<template>
  <div>
    <div class='flex'>
      <div class="lg:w-1/2 w-full h-screen">
        <div class="h-screen flex flex-col justify-center items-center w-2/3 container mx-auto">
          <div class="mb-10">
            <div class="text-3xl font-hairline text-center">Welcome to <span class="font-bold">mpac.com</span></div>
            <div class="text-grey-darkest font-hairline py-2 text-center">We're so glad you're here.  Lets start by logging in.</div>
          </div>

          <input v-model="creds.username" type="text" class="input-field focus:outline-none focus:shadow-outline mb-4" placeholder="username">
          <input v-model="creds.password" type="password" class="input-field focus:outline-none focus:shadow-outline mb-8" placeholder="password">
          <button @click.prevent="submit()" class="bg-blue hover:bg-blue-dark text-white font-bold py-3 px-4 rounded-full w-full">Login</button>
        </div>
      </div>

      <div class="h-screen w-1/2 bg-red-light relative lg:flex items-center hidden">
        <div class="absolute flex justify-center items-center">
          <img src="~assets/images/house.svg"  class="w-2/3"/>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      creds: {
        username: '',
        password: '',
      }
    }
  },

  methods: {
    submit() {
      this.$emit('credentials', this.creds);
    }
  }

}
</script>

<style scoped>
.input-field {
  @apply shadow appearance-none border rounded w-full py-2 px-3 text-grey-darker leading-tight
}
</style>
