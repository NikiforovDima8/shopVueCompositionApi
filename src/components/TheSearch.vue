<script setup>
import MyInput from './MyInput.vue'
</script>

<template>
  <div class="search">
    <div>
      <a href="#">Journal |</a>
      <a href="#"> Search</a>
    </div>
    <div>
      <a href="#">Login | </a>
      <a href="#"
        ><img class="basket" src="@/assets/img/shopping-cart_icon-icons.com_72552.png" alt="Buy"
      /></a>
    </div>
  </div>

  <div>
    <MyInput />
  </div>
</template>

<style>
.search {
  display: flex;
  font-size: 15px;
  column-gap: 50px;
  align-items: center;
  
}
.basket {
  width: 15px;
  margin-left: 8px;
}
</style>
