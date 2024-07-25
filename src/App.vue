<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue';
</script>

<template>
  <div class="flex justify-between h-screen bg-[#f2f5f8] overflow-y-auto overflow-x-hidden">
    <div class="pt-[129px] pl-[63px] pr-[63px] border-r-1 border-[#bfbfbf]">
      <div class="w-[403px] h-[703px] bg-white rounded-[30px] flex flex-col items-center pt-[56px]">
        <img class="border-4 border-[#cfcfcf] rounded-[50%] w-[145px] h-[145px]" src="./assets/dog.jpg" />
        <div class="text-base font-bold text-black pt-[23px]">努力挣钱的小鑫</div>
        <div class="text-sm text-[#00bc91] pt-[15px]">前端工程师</div>
        <div class="w-[339px] h-[1px] bg-[#eeeeee] my-[36px]"></div>
      </div>
    </div>
    <div class="flex-1"></div>
  </div>
</template>

<style scoped></style>
