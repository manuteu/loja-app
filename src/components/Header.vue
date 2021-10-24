<template>
  <div class="headerContainer">
    <div>
      <p class="logo">LOGO</p>
    </div>
    <div>
      <input type="search" placeholder="Pesquisa" class="inputSearch" />
    </div>
    <div class="iconsContainer">
      <img src="../assets/heart-header.png" alt="Coração" class="heart" />
      <img src="../assets/cart.png" alt="Carrinho de Compras" class="cart" />
    </div>
  </div>
</template>
<script>
export default {
  name: "Header",
};
</script>
<style scoped >
.headerContainer {
  height: 70px;
  background-color: #8dd7cf;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}
.logo {
  font-size: 24px;
  margin-left: 65px;
  color: white;
}
.inputSearch {
  height: 55px;
  padding-left: 30px;
  width: 460px;
  line-height: 30px;
  box-sizing: border-box;
  font-size: 18px;
  border: 1px solid #97bec3;
  color: #c3cfd9;
  outline: none;
  border-radius: 4px;
  transition: border-color 0.2s ease;
  background: #fff url(../assets/lupa.png) 96% 48% no-repeat;
  background-size: 20px;
  vertical-align: middle !important;
  align-items: center;
}
.iconsContainer {
  margin-right: 50px;
}
.heart {
  height: 30px;
  width: 30px;
}
.cart {
  height: 30px;
  width: 30px;
  margin-left: 20px;
}
</style>
