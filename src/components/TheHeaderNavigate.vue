<script setup>
import {navigateItem} from '../constants'
</script>


<template>
<div>
      <ul class="navigate">
        <li v-for="option of navigateItem">
          <a :href="`#${option}`">{{option}}</a>
        </li>
      </ul>
    </div>
</template>


<style>

.navigate {
  display: flex;
  column-gap: 32px;
  font-size: 16px;
}
</style>