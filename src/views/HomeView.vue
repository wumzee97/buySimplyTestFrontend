<script lang="ts" setup>
import LoginForm from '@/components/LoginForm.vue';
</script>

<template>
  <div class="w-screen h-screen flex">
    <div class="w-1/2 bg-[#F8EAFF] h-screen px-14 pt-6 hidden lg:inline">
      <img src="../assets/images/logo.svg" alt="" />
      <div class="h-[80vh] flex flex-col items-center justify-center">
        <img src="../assets/images/image.png" class="mt-10" alt="" />
        <h3 class="font-bold font-lora text-xl text-center text-[#61227D] mt-10">
          Team Achieve
        </h3>
        <p class="mt-3  text-lg text-[#5E5E5E] font-bold text-center">Your perfect solution for funding your  desires</p>
      </div>
    </div>
    <div class="lg:w-1/2 w-full flex items-center justify-center flex-col lg:px-32 px-5">
      <img src="../assets/images/logo.svg" class="mb-10 mt-6 lg:hidden" width="198"  alt="" />

    <h3 class="text-center font-bold text-[#61227D] text-[32px]">Welcome Back</h3>
    <p class="text-[#5E5E5E] mb-10 text-center">Enter your email address and password to access your account.</p>

    <LoginForm />
    </div>
  </div>
</template>
