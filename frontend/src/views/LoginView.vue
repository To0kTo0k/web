<template>
  <div class="content">
    <div class="content-block border border-1 border-dark rounded-3">
      <form>
        <div class="mb-3">
          <label for="exampleInputEmail1" class="form-label content-title">Адрес электронной почты</label>
          <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
        </div>
        <div class="mb-3">
          <label for="exampleInputPassword1" class="form-label content-title">Пароль</label>
          <input type="password" class="form-control" id="exampleInputPassword1">
          <div id="emailHelp" class="form-text">Ваш пароль должен состоять из 8-20 символов, содержать буквы и цифры и не должен содержать пробелов, специальных символов или эмодзи.</div>
        </div>
        <div class="mb-3 form-check">
          <input type="checkbox" class="form-check-input" id="exampleCheck1">
          <label class="form-check-label" for="exampleCheck1">Проверить меня</label>
        </div>
        <button type="submit" class="btn btn-primary">Отправить</button>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: 'LoginView',
  components: {}
}
</script>

<style>
  .content {
    flex: 1 0 auto;
    display: flex;
    flex-direction: column;
    min-height: calc(100vh - 70px);
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
</style>
