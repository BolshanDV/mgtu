<template>
  <div class="">
    <div class="row_position">
      <div class="main_section column">
        <h1>Московский государственный технический</h1>
        <h1>университет имени Н. Э. Баумана</h1>
        <div class="title">
          Факультеты участвующие в проекте
        </div>
        <div>
          <p>
            Информатика, искусственный интеллект и системы управления
          </p>
        </div>
        <div>
          <p>
            Инженерный бизнес и менеджмент
          </p>
        </div>
        <div>
          <p>
            Машиностроительные технологии
          </p>
        </div>
        <div>
          <p>
            Специальное машиностроение
          </p>
        </div>
        <div>
          <p>
            Биомедицинская техника
          </p>
        </div>
        <div>
          <div>
            <p>
              Радиоэлектроника и лазерная техника
            </p>
          </div>
          <div>
            <p>
              Факультет Энергомашиностроение
            </p>
          </div>
        </div>
      </div>
      <div class="main_section row_position">
        <img src="../../assets/icons/MGTU.jpeg" alt="" class="img">
      </div>
    </div>
    <div class="row_position contact_section">
      <div class="column">
        <div class="title">Контакты</div>
        <div>
          <p>Телефон: +7 499 263-63-91, +7 499 263-65-41, +7 499 263-66-07</p>
        </div>
        <div>
          <p>Сайт: bmstu.ru</p>
        </div>
        <div>
          <p>Адрес: Россия, Москва, 2-я Бауманская улица, 5, стр. 1</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MGTU"
}
</script>

<style scoped>
.row_position{
  width: 100%;
}
.main_section{
  width: 50%;
  justify-content: center;
}
.img{
  height: 40vh;
  width: 55vh;
}
.img_section{
  width: 20%;
}
.contact_section{
  justify-content: center;
  /*margin: 3vh 5vh;*/
}
</style>
