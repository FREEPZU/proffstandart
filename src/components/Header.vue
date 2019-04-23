<template>
  <div class="">
    <div class="d-flex justify-content-end px-menu bg-request request-size">
      <nav class="pt-2">
        <a class="text-muted" href="#">8-800-775-49-28</a>
        <a class="text-underline pr-0" href="#">Заказать звонок методиста</a>
      </nav>
    </div>
    <div class="d-flex align-items-center py-3 px-menu bg-white border-bottom shadow-sm">
        <img :src="require('../assets/logo.png')" alt="PROFSTANDART" width="184" height="30" class="my-0 mr-md-auto">
        <nav class="my-2 my-md-0 mr-md-nav">
          <a class="p-3 text-underline" href="#">Платформа</a>
          <a class="p-3 text-underline" href="#">О нас</a>
          <a class="p-3 text-underline" href="#">Блог</a>
          <a class="p-3 text-underline" href="#">Отзывы</a>
          <a class="p-3 text-underline" href="#">Контакты</a>
        </nav>
        <a class="btn btn-login" href="#">Войти в кабинет</a>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class Header extends Vue {}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .px-menu {
    padding: 0px 200px;
  }
  .mr-md-nav {
    padding-right: 87px;
  }
  a {
    text-decoration: none;
  }
  .text-underline {
    font-size: 15px;
    color: #20316a;
    padding: 0px 15px;
    text-decoration: underline;
    text-decoration-color: rgba(32,49,106,.22);
  }
  .btn-login {
    border-radius: 5px;
    border: 2px solid #203069;
  }
  a.btn.btn-login {
    color: #203069;
  }
  .bg-request {
    background-color: #f8f8f8;
  }
  .request-size {
    height: 40px;
  }
</style>
