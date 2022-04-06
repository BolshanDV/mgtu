<template>
<div class="row_position main">
  <div class="column">
    <div class="row_position title">
      Заполните форму вашего заказа
    </div>
    <div class="work_space_element_title">
      Фамилия Имя Отчество
    </div>
    <div class="text-field">
      <input class="text-field__input input_element"
             autocomplete="off"
             placeholder="Введите ФИО"
             type="search"
             name="search">
    </div>
    <div class="work_space_element_title">
      Контактный телефон
    </div>
    <div class="text-field">
      <input class="text-field__input input_element"
             autocomplete="off"
             placeholder="Введите телефон"
             type="search"
             name="search">
    </div>
    <div class="work_space_element_title">
      Почта для обратной связи
    </div>
    <div class="text-field">
      <input class="text-field__input input_element"
             autocomplete="off"
             placeholder="Введите почту"
             type="search"
             name="search">
    </div>
    <div class="work_space_element_title">
      Название изделия
    </div>
    <div class="text-field">
      <input class="text-field__input input_element"
             autocomplete="off"
             placeholder="Введите название изделия"
             type="search"
             name="search">
    </div>
    <div class="work_space_element_title">
      Область разработки
    </div>
    <div class="text-field">
      <input class="text-field__input input_element"
             autocomplete="off"
             placeholder="Введите область разработки"
             type="search"
             name="search">
    </div>
    <div class="work_space_element_title">
      Перечень необходимого оборудования
    </div>
    <div class="text-field">
      <input class="text-field__input input_element"
             autocomplete="off"
             placeholder="Введите перечень необходимого оборудования"
             type="search"
             name="search">
    </div>
    <div class="work_space_element_title">
      Комментарии к заказу
    </div>
    <div class="text-field">
      <input class="text-field__input input_element"
             autocomplete="off"
             placeholder="Введите комментарии к заказу"
             type="search"
             name="search">
    </div>
    <div class="work_space_element_title">
      Ссылка на конструкторскую документацию изделия
    </div>
    <div class="text-field">
      <input class="text-field__input input_element"
             autocomplete="off"
             placeholder="Вставьте ссылку"
             type="search"
             name="search">
    </div>
    <nuxt-link to="result">
      <div class="row_position navbar_btn btn">

        Создать заказ
      </div>
    </nuxt-link>

  </div>
</div>
</template>

<script>
export default {
  name: "ApplicationComponent"
}
</script>

<style scoped>
.main{
  justify-content: flex-start;
  /*width: 60vw;*/
  margin: 5vh 0;
}
.column{
  width: 50vw;
}
.work_space_element_title{
  margin-top: 3.75%;
  margin-bottom: 2.75%;
}
.title{
  justify-content: center;
}
.btn{
  /*width: 20vw;*/
  height: 6%;
  background: #73409a;
  border-radius: 7px;
  margin: 3vw 0;
  padding: 1% 2%;
  text-decoration: none;
}
.navbar_btn{
  color: #FFFFFF;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: row;
}
</style>
