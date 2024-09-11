<script setup>
import DrawerHead from './DrawerHead.vue'
import CartItemList from './CartItemList.vue'
</script>

<template>
  <div class="fixed top-0 left-0 h-full w-full bg-black z-10 opacity-70"></div>
  <div class="bg-white w-96 h-full fixed top-0 right-0 z-20 p-8">
    <DrawerHead></DrawerHead>

    <CartItemList></CartItemList>
    <div class="flex flex-col gap-4 mt-5">
      <div class="flex">
        <span>Итого:</span>
        <div class="flex-1"></div>
        <b>25000 руб.</b>
      </div>
      <div class="flex">
        <span>Налог 5%:</span>
        <div class="flex-1"></div>
        <b>750 руб.</b>
      </div>
      <button
        disabled=""
        class="cursor-pointer disabled:bg-slate-400 transition bg-lime-500 w-full rounded-lg py-3 hover:bg-lime-600 active:bg-lime-700"
      >
        Оформить заказ
      </button>
    </div>
  </div>
</template>
