<template>
  <div class="empty_layout">
    <div class="wave">
      <div class="wave_one"></div>
      <div class="wave_two"></div>
      <div class="wave_three"></div>
    </div>
    <Nuxt/>
  </div>
</template>

<script>
export default {
  name: "Empty"
}
</script>

<style scoped>
.empty_layout{
  display: flex;
  min-height: 100vh;
  min-width: 200px;
  width: 100%;
  flex-direction: row;
  justify-content: center;
  align-content: center;
  background-color: #ffffff;
  color: #FFFFFF;
  overflow: hidden;
}
.wave{
  overflow: hidden;
  width: 100%;
  position: relative;
}

.wave_one, .wave_two, .wave_three{
  width: 200vh;
  height: 180vh;
  position: absolute;
}
.wave_one{
  left: -90vh;
  top: 5vh;
  background: radial-gradient(circle farthest-corner at 100px 55px, #7555c7, #78d5b7);
  border-radius: 48%;
  animation: wave 50s linear infinite;
  /*z-index: 1;*/
}
.wave_two{
  left: 40vh;
  top: 65vh;
  background: radial-gradient(circle farthest-corner at 100px 55px, #7d66bb, #528880);
  border-radius: 44%;
  animation: wave 40s linear infinite;
  z-index: 2;
}
.wave_three{
  left: 60vh;
  top: -10vh;
  background: radial-gradient(circle farthest-corner at 100px 55px, #63b29a, #528088);
  border-radius: 43%;
  animation: wave 25s linear infinite;
}
@keyframes wave {
  100% {
    transform: rotate(360deg);
  }
}
</style>
