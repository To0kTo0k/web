<template>
  <div class="content">
    <div class="container-fluid">
        <div class="row">
            <!-- Content title -->
            <div class="col-md-6">
                <div class="content-block border border-1 border-dark rounded-3">
                    <div class="content-title">
                        Москва
                    </div>
                    <div class="content-description">
                        <p>Метро Чкаловская</p>
                        <p>1-ый Сыромятнический переулок, д. 37, офис 14</p>
                        <p>Номер телефона: 89500000000</p> 
                    </div>
                </div>
            </div>
            <!-- Content title -->
            <div class="col-md-6">
                <div class="content-block border border-1 border-dark rounded-3">
                    <div class="content-title">
                        Белгород
                    </div>
                    <div class="content-description">
                        <p>Проспект Богдана Хмельницкого, д. 100</p>
                        <p>Номер телефона: 89800000000</p> 
                    </div>
                </div> 
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutView',
  components: {}
}
</script>

<style>
  .content{
    flex: 1 0 auto;
    display: flex;
    min-height: calc(100vh - 70px);
    flex-direction: column;
    /* Фон */
    background-image: url(../assets/mainPageBg1.jpg);
    background-size: cover;
  }
  .content-block{
    /* Отступы */
    margin: 5%;
    padding: 5%;
    /* Текст */
    text-align: center;
    color:ghostwhite;
    /* Фон */
    background: linear-gradient(rgb(62, 62, 65), rgb(48, 44, 45));
    /* Тени */
    box-shadow: 5px 5px 5px rgb(61, 60, 60);
    text-shadow: rgb(2, 2, 2) 10px 10px 7px;
  }

  img{
      /* Закругление углов изображения */
      border-radius: 20px;
  }

  /* Шрифты */
  .d-inline{
      font-size: 30px;
  }
  .content-title{
      font-size: 24px;
      font-family: fantasy;
  }
</style>