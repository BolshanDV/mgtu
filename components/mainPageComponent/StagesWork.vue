<template>
<div class="row_position">
  <div class="column description">
      <div class="row_position item_description title">
        Механизм работы
      </div>
      <div class="row_position item_description title">
        1. Оформление заказа
      </div>
      <div class="row_position item_description title">
        2. Отправка на рассотрение заказа исполнителем
      </div>
      <div class="row_position item_description title">
        3. В ближайшее время с вами свяжется представитель университета
      </div>

  </div>
  <div class="column">
    фото
  </div>
</div>
</template>

<script>
export default {
  name: "stagesWork"
}
</script>

<style scoped>
.row_position{
  height: 100%;
}
.column{
  align-items: flex-start;
  width: 50%;
  height: 50%;
}
.item_description{
  height: 10%;
}
</style>
