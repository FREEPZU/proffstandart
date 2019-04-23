<template>
  <section class="staff-training text-center">
    <div class="container d-flex flex-column align-items-center">
      <h1 class="text-white pb-5">Обучаем сотрудников без отрыва от работы 
        по охране труда и рабочим профессиям
      </h1>
      <div class="d-flex">
        <input id="icon" type="text" placeholder="Поиск" />
        <button class="ml-4 btn btn-find text-white" href="#">Найти программу</button>
      </div>
      <div class="information d-flex flex-wrap justify-content-between align-items-stretch">
        <article class="information-card">
          <div class="d-flex flex-column">
            <span class="text-white px-3 center-text-card">
              В системе более 200 курсов
            </span>
          </div>
        </article>
        <article class="information-card ml-3">
          <div class="d-flex flex-column">
            <span class="text-white px-3 center-text-card">
              Более 1500 обучающих материалов 
            </span>
          </div>
        </article>
        <article class="information-card ml-3">
          <div class="d-flex flex-column">
            <span class="text-white px-3 center-text-card">
              На 60% дешевле очного обучения
            </span>
          </div>
        </article>
        <article class="information-card ml-3">
          <div class="d-flex flex-column">
            <span class="text-white px-3 center-text-card">
              Помощь методистов в обучении
            </span>
          </div>
        </article>
        <article class="information-card ml-3">
          <div class="d-flex flex-column">
            <span class="text-white px-3 center-text-card">
              Автоматические рассылки,контроль тестирования
            </span>
          </div>
        </article>
        <article class="information-card ml-3">
          <div class="d-flex flex-column">
            <span class="text-white px-3 center-text-card">
              Лицензия No10294 от МинТруда
            </span>
          </div>
        </article>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
export default {};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.staff-training {
  background-image: url(../assets/study.png);
  background-repeat: no-repeat;
  background-size: cover;
  height: 680px;
}
.container {
  padding-top: 88px;
}
h1 {
  font-size: 48px;
}
input {
  text-indent: 17px;
  border-radius: 5px;
  height: 60px;
  background-color: #ffffff;
}
#icon {
  width: 360px;
  background-image: url(../assets/search.png);
  background-repeat: no-repeat;
  background-position: 315px 15px;
}
.btn-find {
  width: 248px;
  height: 60px;
  border-radius: 5px;
  background-color: #f16c00;
  background-image: linear-gradient(to top, #de7d00 0%, #f6af19 100%);
}
.information {
  padding-top: 107px;
}
.information-card {
  width: 169px;
  height: 133px;
  border-radius: 5px;
  background-color: #121e45;
  position: relative;
}
.font-size {
  font-size: 15px;
}
.center-text-card {
  position: absolute;
  top: 50%;
  transform: translate(0, -50%);
}
</style>
