<template>
<div class="column">
  <nuxt-link
      to="/request/directions"
      class="url"
  >
    Разместить заявку
  </nuxt-link>
</div>
</template>

<script>
export default {
  name: "MainPage"
}
</script>

<style scoped>
.column{
  align-items: center;
  height: 100%;
  justify-content: center;
}
.row_position{
  text-decoration: none;
}
</style>
