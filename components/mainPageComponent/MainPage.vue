<template>
<div class="column">
  <nuxt-link
      to="/request/form"
      class="url"
  >
    <div class="row_position row_position_btn_form">
      Разместить заявку
    </div>
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
