<template>
<div class="row_position">
  <div class="column description">
      <div class="item_description">
        описание 1
      </div>
      <div class="item_description">
        описание 2
      </div>
      <div class="item_description">
        описание 3
      </div>
      <div class="item_description">
        описание 4
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
  align-items: center;
  width: 50%;
}
</style>
