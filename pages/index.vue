<template>
  <div class="login">
    <nuxt-link
        to="/home-page"
        class="url"
    >
      <div class="title item">
        Всероссийский производственный аутсорсинг
      </div>
      <div class="title item">
        "Моя инженерия"
      </div>
    </nuxt-link>

  </div>
</template>

<script>

export default {
  name: "login",
  layout: 'empty',
}
</script>

<style scoped>
img{
  width: 130px;
  height: 53px;
}
.login{
  margin-top: 25vh;
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
  align-content: center;
  align-items: center;
  position: absolute;
}
.title{
  font-weight: 300;
  font-size: 45px;
  line-height: 45px;
  margin-top: 20px;
}
.item{
  margin-top: 30px;
  text-align: center;
}
.url{
  color: #FFFFFF;
  text-decoration: none;
}
</style>
