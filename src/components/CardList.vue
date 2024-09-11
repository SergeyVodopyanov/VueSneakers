<script setup>
import Card from './Card.vue'
const onClickAdd = () => {
  alert('Добавлено в корзину')
}
</script>

<template>
  <div class="grid grid-cols-4 gap-5">
    <Card
      imageUrl="/sneakers/sneakers-1.jpg"
      title="Мужские кроссовки Nike Blazer Mid Suede"
      :price="12999"
      :isFavorite="true"
      :onClickAdd="onClickAdd"
    ></Card>
    <Card></Card>
  </div>
</template>
