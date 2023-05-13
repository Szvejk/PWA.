<template>
  <div class="nav">
    <div class="left-nav item2">
      <span><NuxtLink to="/">Strona domowa</NuxtLink></span>
      <span><NuxtLink to="/onas">O nas</NuxtLink></span>
    </div>
  </div>
</template>

<script></script>
<style scoped>
.nav {
  display: flex;
  /* flex-direction: column; */

  background-color: black;
  height: 100%;
  width: 100%;
  max-height: 200px;
  min-height: 200px;
  max-width: 100vw;
  min-width: 200px;
}

.left-nav {

  max-height: 100px;
  min-height: 100px;
  max-width: 50px;
  min-width: 50px;
}

/* px, rem, em, vh, vw, % */
.item {

  max-height: 100px;
  min-height: 100px;
  max-width: 100px;
  min-width: 100px;
}
.item2 {
  display: flex;
  flex-direction: column;
}
</style>
