<script lang="ts" setup>
import EyeIcon from '../components/icons/IconEye.vue'
function handleSubmit() {}
</script>

<template>
  <form @submit.prevent="handleSubmit" class="w-full">
    <label for="email" class="">Email Address *</label>
    <input
      type="text"
      name="email"
      placeholder="Enter your email"
      class="h-12 mt-2 mb-8 text-[#7D7D7D] text-sm w-full border outline-none border-[#ddd] rounded-lg px-4"
    />

    <label for="password" class=" ">Password *</label>
    <div class="border border-[#ddd] mt-2 flex rounded-lg">
      <input
        type="password"
        name="password"
        placeholder="Enter your email"
        class="h-12 text-[#7D7D7D] text-sm w-full rounded-lg outline-none  px-4"
      />
      <div class="border-l border-[#ddd] w-14 bg-[#F7F7F7] rounded-r-lg flex items-center justify-center">
        <EyeIcon />
      </div>
    </div>

    <div class="flex justify-between mt-3">
    <div class="flex">
    <input name="remember" id="remember" type="checkbox" >
    <label class="ml-2" for="remember">Remember me
    
    </label>
    </div>

    <RouterLink to="#" class="text-[#61227D] text-sm">Forgot Password?</RouterLink>
    </div>

    <button type="submit" class="w-full bg-[#61227D] h-12 rounded-lg mt-12 font-bold text-white">Sign in</button>
  </form>

  <p class="text-center text-[#5E5E5E] mt-3">Don’t have an account? <RouterLink to="#" class="text-[#61227D] font-semibold">Sign Up</RouterLink></p>
</template>
