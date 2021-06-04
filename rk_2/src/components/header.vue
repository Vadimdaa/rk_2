<template>
  <header class="header">
    <div class="container">
      <div class="header__inner">
        <div class="header__logo">
          <img class="header__logo__img" src="https://upload.wikimedia.org/wikipedia/commons/9/90/LogoMospolytech.jpg" alt="лого" />
        </div>
        <nav class="header__nav nav">
          <ul class="nav__list">
            <li class="nav__li"><a href="#recipe" tabindex="1">Пироги</a></li>
            <li class="nav__li"><a href="#bulki" tabindex="2">Булки</a></li>
            <li class="nav__li"><a href="#milk" tabindex="3">Молоко</a></li>
          </ul>
          <button tabindex="4" class="change-color">Изменить тему</button>
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
.header__inner {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.header__nav {
  display: flex;
  align-items: center;
}
.nav__list {
  display: flex;
  font-size: 1.5rem;
  padding-right: 1rem;
}
.nav__li:not(:first-of-type) {
  padding-left: 1rem;
}
</style>
