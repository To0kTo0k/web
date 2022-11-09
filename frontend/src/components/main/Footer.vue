<template>
    <footer>
        <!-- Текст внутри блока выровнен по правому краю. Цвет фона блока #2a2a2a, значения полей от блока до его содержимого равно 1em, цвет текста внутри блока белый (#fff) -->
        <div class="footer">
            © Print4U <br>2022
        </div>
    </footer>
</template>

<script>
    export default {
      name: "Footer"
    }
</script>

<style scoped>
  .footer{
    height: 70px;
    text-align:right;
    background:#2a2a2a;
    padding: 13px;
    color: #fff;
  }
</style>