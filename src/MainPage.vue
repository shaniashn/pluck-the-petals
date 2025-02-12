<template>
  <section class="all-flower">
    <div class="flower">
    <!-- <div class="core-petal"><img src="./assets/core-petal.svg" alt="core-petal"></div> -->
     <div class="flower-ex"><img src="./assets/image.png" alt=""></div>
  </div>
  </section>
</template>

<script>
export default {
  name: 'MainPage'
}
</script>

<style>
.all-flower {
  height: 100vh;
  display: grid;
  align-items: center;
}

.flower {
  margin: auto 0;
  /* background-color: aqua; */
}
.core-petal {
  width: 10%;
}

.flower-ex img {
  transition: transform 2s ease-in-out;
}

.flower-ex img:hover {
  transform: rotate(360deg);
}


</style>