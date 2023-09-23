<script setup>
import TheCards from './components/TheCards.vue'
import TheLogo from './components/TheLogo.vue'
import TheNavItem from './components/TheNavItem.vue'
import TheHeaderNavigate from './components/TheHeaderNavigate.vue'
import TheSearch from './components/TheSearch.vue'
</script>

<template>
  <header class="header">
    <TheLogo />
    <TheHeaderNavigate />
    <TheSearch />
  </header>
  <div>
    <img class="titleImg" src="./assets/img/Frame1.png" alt="TitleImg" />
  </div>

  <TheNavItem />
  <main>
    <div class="container">
      <TheCards />
    </div>
  </main>
</template>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'Roboto', sans-serif;
  text-decoration: none;
  list-style-type: none;
  max-width: 1440px;
}
body {
  overflow-x: hidden;
}

header {
  width: 100%;
  display: flex;
  justify-content: space-around;
  align-items: center;
padding: 15px;
  column-gap: 50px;
background-color: rgb(160, 122, 79);
}
a,
h3 {
  color: #000000b5;
}

.titleImg {
  width: 1440px;
  height: 600px;

}

.container {
  width: 1180px;
  margin: 0 auto;
  margin-top: 25px;
  overflow: auto;
}
</style>
