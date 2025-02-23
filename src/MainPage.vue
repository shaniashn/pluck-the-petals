<template>
  <section class="all-flower">
  <h2>pluck the petals</h2>
    <div class="flower">
     <div class="flower-addition"><img src="./assets/flower-addition-.svg" alt=""></div>
     <div class="flower-core"><img src="./assets/flower-core.svg" alt=""></div>
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
  overflow: hidden;
  height: 100vh;
}

.flower {
  /* background-color: rgb(0, 255, 255, 0.5); */
  width: 100%;
  height: 100%;
  /* position: relative; */
  display: flex;
  justify-content: center;
  align-items: center;
}

.flower .flower-core {
  /* margin: auto 0; */
  width: 30%;
  /* background-color: rgb(0, 55, 255, 0.5); */
  /* position: relative; */
  
  position: absolute;
}

.flower .flower-addition {
  width: 50%;
  transform: translateX(50%);
  /* justify-content: end; */
  position: absolute;
  bottom: 0;
}

.flower-core img {
  transition: transform 2s ease-in-out;
}

.flower-core img:hover {
  transform: rotate(360deg);
}

</style>