<template>
  <div class="row_position main_block">
    <div class="row_position order_item">
      Заказ 1
    </div>
    <div class="row_position order_item ">
      Заказ 2
    </div>
    <div class="row_position order_item">
      Заказ 3
    </div>
    <div class="row_position order_item ">
      Заказ 4
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
</style>
