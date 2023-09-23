<script setup>
import {slides} from '../constants'

</script>

<template>
   <div class="cards">
        <a v-for="(name, item) of slides" :key="item" :href="`#${name.title}`">
        <img :src="name.img" alt="name.title">
          <h3>{{name.title}}</h3>
          <p>{{name.price}}<span> $130.00</span></p>
        </a>
      </div>

</template>

<style>
.cards{
  display: grid;
  grid-template-columns: repeat(4,310px);
  grid-row-gap: 25px;
  overflow: hidden;
}
.cards span {
  color: red;
}
</style>