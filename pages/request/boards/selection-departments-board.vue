<template>
  <div class="row_position main">
    <div class="column">
      <div class="row_position title">
        Выберете кафедру
      </div>
      <div class="row_position work_space_element_title">
        <input
          type="checkbox"
          class="switch_1"
        >
        1
      </div>
      <div class="row_position work_space_element_title">
        <input
            type="checkbox"
            class="switch_1"
        >
        2
      </div>
      <div class="row_position work_space_element_title">
        <input
            type="checkbox"
            class="switch_1"
        >
        3
      </div>
      <div class="row_position work_space_element_title">
        <input
            type="checkbox"
            class="switch_1"
        >
        4
      </div>
      <div class="row_position btn_element">
        <div class="row_position btn">
          <nuxt-link to="/request/directions">
            <div class=" navbar_btn">
              Назад
            </div>
          </nuxt-link>
        </div>
        <div class="row_position btn">
          <nuxt-link to="/request/result">
            <div class="navbar_btn">
              Продолжить
            </div>
          </nuxt-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "selection-departments-board"
}
</script>

<style scoped>
.main{
  justify-content: flex-start;
  height: 70vh;
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
.navigator{
  justify-content: center;
}
.text_element{
  color: rgba(0,0,0,1);
  text-decoration: none;
}
.btn{
  /*width: 20vw;*/
  height: 6vh;
  background: #73409a;
  border-radius: 7px;
  /*margin: 3vw 0;*/
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
