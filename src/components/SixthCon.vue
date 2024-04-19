<template>
  <div class="con py-28 px-8">
    <div class="max-w-5xl mx-auto">
      <div class="mainText flex justify-center" id="reviews">Отзывы</div>
      <div class="flex items-center max-w-6xl mx-auto py-14 space-x-6">
        <div class="flex flex-col items-center space-y-4">
          <img src="../assets/avatar.png" class="rounded-full w-64" alt="" />
          <span class="name"> Anna.M </span>
        </div>
        <div class="bordered">
          Очень красивые и нежные приглашения! Любовь с первого взгляда! Плюс
          интересный вариант отправки приглашений в электронном виде - для тех
          гостей, у которых нет возможности лично вручить бумажный вариант. Буду
          рекомендовать при первой возможности!
        </div>
      </div>
      <div class="flex items-center max-w-6xl mx-auto py-14 space-x-6">
        <div class="bordered">
          Очень удобный и максимально простой сервис для создания приглашений на
          любой вкус и цвет. Мне все очень понравилось, особенно большое
          разнообразие вариантов, а также компетентный и вежливый персонал! Всем
          советую)
        </div>
        <div class="flex flex-col items-center space-y-4">
          <img src="../assets/avatar.png" class="rounded-full w-64" alt="" />
          <span class="name"> Emma.W </span>
        </div>
      </div>
      <div class="flex items-center max-w-6xl mx-auto py-14 space-x-6">
        <div class="flex flex-col items-center space-y-4">
          <img src="../assets/avatar.png" class="rounded-full w-64" alt="" />
          <span class="name"> Stanislav.B </span>
        </div>
        <div class="bordered">
          Очень удобный и максимально простой сервис для создания приглашений на
          любой вкус и цвет. Мне все очень понравилось, особенно большое
          разнообразие вариантов, а также компетентный и вежливый персонал! Всем
          советую)
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.con {
  background: #ffffffcc;
}

.bordered {
  border: 3px solid #e3b253;
  background: #ffffffcc;
  padding: 2rem;
}

.mainText {
  font-family: NotoSerifTamilSlanted;
  font-size: 50px;
  font-style: italic;
  font-weight: 500;
  line-height: 120px;
  text-align: left;
  color: #03222ec7;
}

.name {
  font-family: NotoSerifTamilSlanted;
  font-size: 30px;
  font-style: italic;
  font-weight: 500;
  line-height: 20px;
  text-align: center;
  color: #03222ec7;
}
</style>
