<template>
  <div class="row_position main_block">
    <div class="element">
      <nuxt-link to="/partners/MGTU">
        <div class="row_position order_item item1">
          <img src="../../assets/icons/Gerb_MGTU_imeni_Baumana.png" class="img" alt="">
        </div>
        <div class="url">Московский государственный технический университет имени Н. Э. Баумана</div>
      </nuxt-link>

    </div>

    <div class="row_position order_item ">
      Вузы парнеры
    </div>
    <div class="row_position order_item">
      Вузы парнеры
    </div>
    <div class="row_position order_item ">
      Вузы парнеры
    </div>
  </div>
</template>

<script>
export default {
  name: "partners"
}
</script>

<style scoped>
.order_item{
  border-radius: 50%;
  height: 30vh;
  width: 30vh;
  background-color: rgb(173,215,194);
  justify-content: center;
}
.main_block {
  height: 100%;
  justify-content: space-between;
}
.img{
  height: 25vh;
  width: 21vh;
}
.element{
  width: 30vh;
}
.url{
  color: #000000;
  text-decoration: none;
}
</style>
