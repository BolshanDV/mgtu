<template>
  <div class="main_section">
    <div class="main_block column">
      <mainPage/>
    </div>
    <div class="main_block column">
      <stages-work/>
    </div>
    <div class="main_block column">
      <orders/>
    </div>
    <div class="main_block column">
      <reviews/>
    </div>
    <div class="main_block column">
      <partners/>
    </div>
  </div>
</template>

<script>
import mainPage from "@/components/mainPageComponent/MainPage";
import stagesWork from "@/components/mainPageComponent/StagesWork";
import orders from "@/components/mainPageComponent/Orders";
import reviews from "@/components/mainPageComponent/Reviews";
import partners from "@/components/mainPageComponent/Partners";

export default {
  name: "homePage",
  components: {
    mainPage,
    stagesWork,
    orders,
    reviews,
    partners
  }
}
</script>

<style>
.main_block{
  height: 80vh;
}
.main_section{
  padding: 3%;
}
</style>
