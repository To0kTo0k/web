<template>
  <div class="content">
    <div class="container-fluid">
      <div class="row">
        <div class="col-md-6">
          <div class="content-block border border-1 border-dark rounded-3">
            <figure class="text-end">
              <blockquote class="blockquote">
                <p>Отличное качество изготовления! Буду заказывать ещё.</p>
              </blockquote>
              <figcaption class="blockquote-footer">Иванов Иван, Москва</figcaption>
            </figure>
          </div>
        </div>

        <div class="col-md-6">
          <div class="content-block border border-1 border-dark rounded-3">
            <figure class="text-end">
              <blockquote class="blockquote">
                <p>Очень понравилось, заказ выполнен целиком в соответствие с требованиями и в срок.</p>
              </blockquote>
              <figcaption class="blockquote-footer">Петров Петр, Воронеж</figcaption>
            </figure>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'ReviewView',
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