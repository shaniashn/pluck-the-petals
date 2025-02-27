<template>
  <section class="all-flower">
    <h2>pluck the petals</h2>
    <div class="flower">
      <div class="flower-addition"><img src="./assets/flower-addition-.svg" alt=""></div>
      <div class="pollens">
      <div class="pollen"></div>
      <div class="pollen"></div>
      <div class="pollen"></div>
      <div class="pollen"></div>
      <div class="pollen"></div>
      <div class="pollen"></div>
      <div class="pollen"></div>
      <div class="pollen"></div>
    </div>
      <div class="flower-core"><img src="./assets/flower-core.svg" alt=""></div>
    </div>

    
  </section>
</template>

<script>
export default {
  name: 'MainPage'
}
</script>

<style lang="scss">
.all-flower {
  // overflow: hidden;
  height: 100vh;

  .flower {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;

    .flower-core {
      width: 30%;
      position: absolute;

      img {
        animation: rotateFlower 2s 1;

        &:hover {
          transform: rotate(360deg);
          animation: rotateFlower 2s infinite;
        }
      }
    }

    .flower-addition {
      width: 50%;
      transform: translateX(50%);
      position: absolute;
      bottom: 0;
    }
  }

  .pollens {
    // position: absolute;
    width: 100%;
    height: 100%;
    background-color: aquamarine;
    // z-index: -1;

    .pollen {
      width: 0.5%;
      aspect-ratio: 1/1;

      margin-bottom: 10px;
      background-color: yellow;
    }
  }
}

@keyframes rotateFlower {
  0% {
    transform: rotate(0deg);;
  }

  50% {
    transform: rotate(360deg);
  }

  100% {
    transform: rotate(0deg);;
  }
}

</style>