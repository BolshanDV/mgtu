<template>
  <div class="main_section">
    <div class="main_block information_section">
      <mainPage/>
    </div>
  </div>
</template>

<script>
import mainPage from "~/components/mainPage";
export default {
  name: "home",
  components: {
    mainPage
  }
}
</script>
