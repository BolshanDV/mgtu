<template>
  <div class="row_position main">
    <div class="column">
      <div class="row_position title">
        Выберете направление
      </div>
      <div class="row_position work_space_element_title">
        <nuxt-link to="casting" class="text_element">
          Литье
        </nuxt-link>
      </div>
      <div class="row_position work_space_element_title">
        Печатные платы
      </div>
      <div class="row_position work_space_element_title">
        Химические реактивы
      </div>
      <div class="row_position navigator btn">
        <div class="row_position">
          <nuxt-link to="/home-page"
          class="navbar_btn">
              Назад
          </nuxt-link>
        </div>
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: "directions"
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
.navigator{
  justify-content: center;
}
.text_element{
  color: rgba(0,0,0,1);
  text-decoration: none;
}
</style>
