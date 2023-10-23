<template>
  <div class="container">
    <div class="header__container">
      <h1 class="header">Жилфонд</h1>
      <p class="description">Пользователь</p>
    </div>
    <div class="search__container">
      <div class="find">
        <p class="find__description">Поиск сотрудников</p>
        <input
          class="find__input"
          type="text"
          placeholder="Введите id или имя"
        />
        <p class="find__description">Результаты</p>
        <span class="find__item">начните поиск</span>
      </div>
      <div class="about"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Sidebar",
};
</script>

<style src="./../assets/styles/Sidebar.scss" scoped></style>
