<template>
  <div class="content">
    <div class="container-fluid">
      <div class="row">
        <!-- Content title -->
        <div class="col-md-6">
          <div class="content-block border border-1 border-dark rounded-3">
            <div>
              <img src="../assets/mainPage1.jpg" class="img-fluid" alt="Stickers">
            </div>
            <div class="content-title">
              Создание стикеров
            </div>
            <div class="content-description">
              <p>Стикеры - одна из самых эффективных форм рекламы на самоклеящейся основе.</p>
              <p>Используются практически в любой сфере деятельности человека.</p>
              <p>Материал изготовления - бумага или пленка.</p>
            </div>
          </div>
        </div>
        <!-- Content title -->
        <div class="col-md-6">
          <div class="content-block border border-1 border-dark rounded-3">
            <div>
              <img src="../assets/mainPage2.jpg" class="img-fluid" alt="Wear print">
            </div>
            <div class="content-title">
              Принты на одежде
            </div>
            <div class="content-description">
              <p>Доступны шелкография (трафаретная печать) - продавливание краски на изделие через трафарет,</p>
              <p>цифровая печать - нанесение краски на изделение при помощи специального принтера,</p>
              <p>термотрансфер - приплавка пленки с изображением к продукции,</p>
              <p>сублимация - перевод логотипа при помощи пресса с подложки на изделие.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'HomeView',
    components: {}
  }
</script>

<style>
  .content{
    flex: 1 0 auto;
    display: flex;
    flex-direction: column;
    min-height: calc(100vh - 70px);
    /* Фон */
    background-image: url(../assets/mainPageBg1.jpg);
    background-size: cover;
  }
  .content-block{
    margin: 5%;
    padding: 5%;
    text-align: center;
    color:ghostwhite;
    background: linear-gradient(rgb(62, 62, 65), rgb(48, 44, 45));
    box-shadow: 5px 5px 5px rgb(61, 60, 60);
    text-shadow: rgb(2, 2, 2) 10px 10px 7px;
  }
  img{
    border-radius: 20px;
  }
  .d-inline{
    font-size: 30px;
  }
  .content-title{
    font-size: 24px;
    font-family: fantasy;
  }
</style>



