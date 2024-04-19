<template>
  <div
    id="characteristics"
    class="max-w-6xl mx-auto py-28 space-y-32 flex flex-col items-center justify-center lg:grid grid-cols-2 px-8"
  >
    <div
      class="flex space-x-8 items-center mt-32 justify-center w-1/2 lg:w-full"
    >
      <img src="../assets/thirdConImg.svg" alt="" />
      <div class="flex flex-col items-start lg:w-2/3">
        <span class="mainText"> Различные варианты </span>
        <span> Давайте выберем размер, который вам идеально подходит. </span>
      </div>
    </div>

    <div class="flex space-x-8 items-center justify-center w-1/2 lg:w-full">
      <img src="../assets/thirdConImg2.svg" alt="" />
      <div class="flex flex-col items-start lg:w-2/3">
        <span class="mainText"> Материал </span>
        <span> Высококачественная бумага, фольгирование, тиснение </span>
      </div>
    </div>

    <div class="flex space-x-8 items-center justify-center w-1/2 lg:w-full">
      <img src="../assets/thirdConImg3.svg" alt="" />
      <div class="flex flex-col items-start lg:w-2/3">
        <span class="mainText"> Палитра </span>
        <span>
          Цветовая палитра, максимально соответствующая вашему свадебному стилю
        </span>
      </div>
    </div>

    <div class="flex space-x-8 items-center justify-center w-1/2 lg:w-full">
      <img src="../assets/thirdConImg4.svg" alt="" />
      <div class="flex flex-col items-start lg:w-2/3">
        <span class="mainText"> Упаковка </span>
        <span> В комплект поставки входят индивидуальные упаковка </span>
      </div>
    </div>
  </div>
  <div class="py-8 flex justify-between w-full">
    <button class="greenButton mx-auto">Посмотреть</button>
  </div>
</template>

<style scoped>
span {
  font-family: NotoSerifTamilSlanted;
  font-size: 20px;
  font-style: italic;
  font-weight: 500;
  line-height: 30px;
  text-align: left;
}
.mainText {
  font-family: NotoSerifTamilSlanted;
  font-size: 30px;
  font-style: italic;
  font-weight: 500;
  line-height: 30px;
  text-align: left;
}
</style>
