<template>
<div class="row_position">
  <div class="column">
    <div>
      <h1>Заказ успешно создан</h1>
    </div>
    <nuxt-link to="/home-page">
      <div class="row_position navbar_btn btn">
        Вернуться на главную страницу
      </div>
    </nuxt-link>
  </div>

</div>
</template>

<script>
export default {
  name: "result"
}
</script>

<style scoped>
.row_position{
  justify-content: center;
}
.column{
  justify-content: center;
  height: 80vh;
}
</style>
