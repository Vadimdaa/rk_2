<template>
  <main class="main">
    <div class="container">
      <div class="main__inner">
        <h1 class="main__title">Рецепты</h1>
        <section class="main__recipe recipe" id="recipe">
            <hr>
          <h2 class="recipe__title">Пироги</h2>
          <div class="blocks">
            <div class="recipe__block block">
              <h3 class="block__title">Пирог с вишней</h3>
              <p class="block__description">
                Очень вкусный пирог
              </p>
            </div>
            <div class="recipe__block block">
              <h3 class="block__title">Пирог с картошкой</h3>
              <p class="block__description">
                Не очень вкусный пирог
              </p>
            </div>
            <div class="recipe__block block">
              <h3 class="block__title">Пирог со сгущенкой</h3>
              <p class="block__description">
                Ужасный пирог
              </p>
            </div>
          </div>
        </section>
        <section class="main__bulki bulki" id="bulki">
            <hr>
          <h2 class="bulki__title">Булки</h2>
          <div class="blocks">
            <div class="recipe__block block">
              <h3 class="block__title">Булка с кремом</h3>
              <p class="block__description">
                Вкусная булка
              </p>
            </div>
            <div class="recipe__block block">
              <h3 class="block__title">Булка с капустой</h3>
              <p class="block__description">
                Средняя булка
              </p>
            </div>
            <div class="recipe__block block">
              <h3 class="block__title">Булка с печеньем</h3>
              <p class="block__description">
                Такой не существует
              </p>
            </div>
          </div>
        </section>
        <section class="main__milk milk" id="milk">
            <hr>
          <h2 class="milk__title">Молоко</h2>
          <div class="blocks">
            <div class="recipe__block block">
              <h3 class="block__title">Обезжиренное молоко</h3>
              <p class="block__description">
                Надо покупать
              </p>
            </div>
            <div class="recipe__block block">
              <h3 class="block__title">Жирное молоко</h3>
              <p class="block__description">
                Вроде неплохое
              </p>
            </div>
            <div class="recipe__block block">
              <h3 class="block__title">Обычное молоко</h3>
              <p class="block__description">
                Обычное молоко
              </p>
            </div>
          </div>
        </section>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: "Main",
  props: {},
};
</script>

<style>
</style>