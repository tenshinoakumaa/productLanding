<template>
  <div class="con px-8">
    <div class="max-w-6xl mx-auto text-center mainText" id="about">
      Мы всё делаем из бумаги
    </div>
    <div
      class="flex flex-col lg:flex-row items-center max-w-6xl mx-auto py-14 lg:space-x-16"
    >
      <img src="../assets/secondConImg.svg" alt="" />
      <div>
        <div class="bordered">
          Наши свадебные приглашения - это не просто бумажные открытки. Они
          являются символом вашей любви и стиля. Наш эксклюзивный дизайн поможет
          вам подчеркнуть особенность вашего знаменательного дня.
        </div>
      </div>
    </div>
    <div
      class="flex flex-col lg:flex-row items-center max-w-6xl mx-auto py-14 lg:space-x-16"
    >
      <div class="order-1 lg:order-none">
        <div class="bordered">
          Онлайн-дизайнер поможет вам настроить выбранный дизайн как бумажной
          версии, так и сайта-приглашения, чтобы максимально использовать ваш
          свадебный стиль.
        </div>
      </div>
      <img class="lg:mr-14" src="../assets/secondConImg2.svg" alt="" />
    </div>
  </div>
</template>

<style scoped>
.con {
  background: #d9d9d98c;
}

.bordered {
  border: 3px solid #e3b253;
  background: #d9d9d991;
  padding: 2rem;
  font-family: url("../fonts/NotoSerifTamilSlanted-Regular.otf");
}

.mainText {
  font-family: url("../fonts/NotoSerifTamilSlanted-Regular.otf");
  font-size: 50px;
  font-style: italic;
  font-weight: 400;
  line-height: 120px;
}
</style>
