<template>
<div class="row_position">
  <div class="column">
    <h1>Информация о нашем проекте</h1>
    <p>Кто мы</p>
    <p>Для чего создан проект</p>
    <p>На кого он нацелен</p>
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
  name: "about"
}
</script>

<style scoped>
.row_position{
  justify-content: center;
}
.column{
  height: 80vh;
}
.btn{
  color: #FFFFFF;
  background: #73409a;
  border-radius: 7px;
  margin: 0 3%;
  padding: 1% 2%;
  text-decoration: none;
}
</style>
