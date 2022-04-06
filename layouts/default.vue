<template>
    <div class="body">
      <div class="main">
        <div class="navbar row_position">
          <Navbar/>
        </div>
          <div class="scroll">
            <Nuxt/>
            <div class="footer">
              <Footer/>
            </div>
          </div>
      </div>
    </div>
</template>

<script>
import Navbar from "@/components/barElement/Navbar";
import Footer from "@/components/barElement/Footer";
export default {
  name: "Default",
  components: {
    Navbar,
    Footer
  },
}
</script>

<style scoped>
.body{
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  /*background-color: #ffffff;*/
  background: #FFFFFF;
  min-height: 100vh;
}
.main{
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
  width: 100%;
}
.navbar{
  background-color: #7555c7;
  height: 11vh;
}
.footer{
  background-color: #7555c7;
  height: 25vh;
}
.scroll{
  max-height: 90vh;
  scrollbar-width: none;
}
</style>
