<template>
  <div class="navbar_section">
    <div class="btn">
        <div class="navbar_btn">
          Exit
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "navbar",
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
  background: #B41210;
  border-radius: 7px;
  margin: 0 3%;
  padding: 1% 2%;
}
.navbar_btn{
  color: #FFFFFF;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: row;
}
</style>
