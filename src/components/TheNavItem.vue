<script setup>
import {navI} from '../constants'
</script>


<template>
<nav>
    <ul class="navItem">
      <li v-for="i of navI" :key="i">
        <a :href="`#${i}`">{{i}}</a>
      </li>
    </ul>
  </nav>
</template>


<style>
.navItem {
  display: flex;
  column-gap: 48px;
  justify-content: center;
  margin-top: 40px;
}
</style>