<template>
  <div class="row_position main">
    <div class="column">
      <div class="row_position title">
        Литье
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
        Город
      </div>
      <div class="text-field">
        <input class="text-field__input input_element"
               autocomplete="off"
               placeholder="Введите ваш город"
               type="search"
               name="search">
      </div>
      <div class="work_space_element_title">
        Марка
      </div>
      <div class="text-field">
        <input class="text-field__input input_element"
               autocomplete="off"
               placeholder="Введите марку"
               type="search"
               name="search">
      </div>
      <div class="work_space_element_title">
        Объем
      </div>
      <div class="text-field">
        <input class="text-field__input input_element"
               autocomplete="off"
               placeholder="Введите необходимый объем"
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
      <div class="row_position btn_element">
        <div class="btn">
          <nuxt-link to="/request/directions">
            <div class="row_position navbar_btn">
              Назад
            </div>
          </nuxt-link>
        </div>
        <div class="btn">
          <nuxt-link to="selection-departments">
            <div class="row_position navbar_btn">
              Продолжить
            </div>
          </nuxt-link>
        </div>
      </div>
      <Orders/>

    </div>
  </div>
</template>

<script>
import Orders from "@/components/mainPageComponent/Orders";
export default {
  name: "casting",
  components: {
    Orders
  }
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
.btn_element{
  justify-content: space-between;
}
</style>
