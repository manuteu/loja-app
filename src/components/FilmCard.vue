<template>
  <div class="grid-3 cardContainer" id="animar">
    <div class="imageContainer">
      <img src="../assets/imagem.png" alt="Imagem Filme" class="imageFilm" />
      <img src="../assets/heart-card.png" alt="Coração" class="heart" />
      <p class="imageData">7 de Janeiro, 2019</p>
    </div>
    <div class="infoContainer">
      <h1 class="filmName">Nome do Filme</h1>
      <div class="row">
        <img src="../assets/star.png" alt="Estrela" class="star" />
        <p class="numberStar">7</p>
        <p>Gênero</p>
      </div>
      <p>R$ 79,99</p>
      <div>
        <button class="button">Adicionar</button>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>

<style scoped>
.cardContainer {
  margin-top: 42px;
  height: 400px;
}
.imageContainer {
  background-color: #dfe6ed;
  border: 1px solid #9eadba;
  height: 262px;
  border-block-end-color: #dfe6ed;
}
.imageData {
  margin-top: 60px;
  text-align: center;
}
.imageFilm {
  /* position: absolute; */
  margin-top: 50%;
  margin-left: 37%;
}
.heart {
  position: absolute;
  margin-left: 50px;
  margin-top: 14px;
}
.row {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  padding: 7px 0 7px 0;
}
.infoContainer {
  text-align: center;
  /* margin-top: 20px; */
  height: 140px;
  border: 1px solid #9eadba;
}
.filmName {
  font-size: 18px;
  font-weight: bold;
  padding-top: 10px;
  letter-spacing: 0.8px;
}
.star {
  height: 22px;
  width: 22px;
}
.numberStar {
  padding: 2px 12px 0px 6px;
}
.button {
  margin-top: 12px;
  height: 42px;
  border-style: none;
  cursor: pointer;
  color: white;
  background-color: #6558f5;
  width: 100%;
  border-top-right-radius: 4px;
  border-top-left-radius: 4px;
  font-size: 18px;
  letter-spacing: 1px;
  font-weight: bold;
}
</style>