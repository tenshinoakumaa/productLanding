<template>
  <nav
    class="max-w-6xl mx-auto flex items-center justify-between text-white px-4"
  >
    <div class="flex items-center space-x-2">
      <img src="../assets/globalIcon.svg" alt="" />
      <span> AnnieShop </span>
    </div>
    <ul class="lg:flex justify-between w-1/2 hidden">
      <li>
        <a href="#about"> О продукте </a>
      </li>
      <li><a href="#characteristics"> Технические характеристики </a></li>
      <li><a href="#reviews">Отзывы</a></li>
      <li><a href="#footer">Контакты</a></li>
    </ul>
    <img class="lg:hidden" src="../assets/burgerIcon.svg" alt="" />
  </nav>
</template>

<script></script>

<style scoped>
nav {
  border-bottom: 1px solid #e3b253;
}

li {
  cursor: pointer;
}
</style>
