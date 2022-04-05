<template>
    <div class="body">
<!--      <div class="sidebar">-->
<!--        <Sidebar/>-->
<!--      </div>-->
      <div class="main">
        <div class="navbar row_position">
          <navbar/>
        </div>
        <div class="main_section scroll">
          <Nuxt/>
        </div>
      </div>
    </div>
</template>

<script>
import Sidebar from "../components/barElement/sidebar";
import navbar from "../components/barElement/navbar";
export default {
  name: "default",
  components: {
    Sidebar,
    navbar,
  },
}
</script>

<style scoped>
.body{
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  background-color: #161E29;
  min-height: 100vh;
}
.sidebar{
  background: #0D121A;
  width: 20%;
}
.main{
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
  width: 100%;
}
.main_section{
  padding: 3%;
}
.navbar{
  background-color: #080D16;
  height: 11vh;
}
.scroll{
  max-height: 90vh;
  scrollbar-width: none;
}
</style>
