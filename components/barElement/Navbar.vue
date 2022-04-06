<template>
  <div class="navbar_section">
    <nuxt-link
        to="/"
        class="btn"
    >
      <div class="navbar_btn">
        Выход
      </div>
  </nuxt-link>
  </div>
</template>

<script>
export default {
  name: "Navbar",
}
</script>

<style scoped>
.navbar_section{
  flex-direction: row;
  justify-content: flex-end;
  display: flex;
  align-items: center;
  width: 100%;
}
.btn{
  width: 7vw;
  height: 6%;
  background: #73409a;
  border-radius: 7px;
  margin: 0 3%;
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
