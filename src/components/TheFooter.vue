<template>
  <div class="con py-28" id="footer">
    <div id="modal" class="modal" style="display: none">
      <div class="modal-content">
        <span class="close" @click="closeModal">&times;</span>
        <div class="modal-text">
          Конфиденциальность клиентов - наш приоритет. Наша политика
          конфиденциальности разработана для защиты вашей личной информации. На
          нашем лендинге мы не собираем никаких персональных данных без вашего
          согласия. Мы ценим вашу конфиденциальность и стремимся обеспечить
          безопасную среду для посещения нашего сайта. Ниже приведены основные
          принципы нашей политики конфиденциальности: 
          <br>1. Сбор информации: Мы не
          собираем никаких персональных данных о посетителях нашего лендинга без
          их явного согласия. 
          <br>2. Использование информации: Любая предоставленная
          вами информация используется исключительно для ответа на ваши запросы
          и обратной связи. Мы не раскрываем, продаем или передаем вашу личную
          информацию третьим лицам. 
          <br>3. Контактные данные: На нашем лендинге вы
          можете найти контактную информацию для связи с нами. Мы гарантируем
          безопасность и конфиденциальность любой информации, переданной через
          эти каналы связи. 
          <br>4. Безопасность: Мы принимаем меры безопасности для
          защиты вашей личной информации от несанкционированного доступа или
          использования. 
          <br>5. Изменения в политике конфиденциальности: Мы
          оставляем за собой право вносить изменения в нашу политику
          конфиденциальности. Любые изменения будут опубликованы на этой
          странице. Если у вас возникли вопросы или предложения относительно
          нашей политики конфиденциальности, пожалуйста, свяжитесь с нами,
          используя контактную информацию, указанную на нашем лендинге.
        </div>
      </div>
    </div>
    <div
      class="max-w-6xl mx-auto flex lg:flex-row lg:justify-between flex-col items-center lg:items-start space-y-14 lg:space-y-0"
    >
      <div class="div space-y-4 lg:p-12">
        <span class="mainText">Меню сайта</span>
        <ul class="text-white flex flex-col items-start space-y-4">
          <li><a href="#about"> О продукте </a></li>
          <li><a href="#characteristics"> Технические характеристики </a></li>
          <li><a href="#reviews">Отзывы</a></li>
          <li><a href="#footer">Контакты</a></li>
        </ul>
      </div>

      <div class="secondDiv p-12 space-y-4">
        <span class="mainText">Контактная информация</span>
        <div class="flex flex-col items-start">
          <span class="font-bold"> Адрес: </span>
          <span> c.Kaskelen,1/1 Abylai Khan Avenue </span>
        </div>
        <div class="flex flex-col items-start">
          <span class="font-bold"> Телефоны: </span>
          <span> +7 727 307 95 65 </span>
        </div>
        <div class="flex flex-col items-start">
          <span class="font-bold"> Email: </span>
          <span> annieShop@sdu.edu.kz </span>
        </div>
        <div class="flex items-center justify-between">
          <span class="font-bold">Быстрая связь в мессенджерах</span>
          <div class="flex space-x-4">
            <img src="../assets/telegramIcon.svg" alt="" />
            <img src="../assets/instagramIcon.svg" alt="" />
            <img src="../assets/whatsappIcon.svg" alt="" />
          </div>
        </div>
      </div>
    </div>
    <div class="flex justify-center text-center pt-28">
      <span class="footer-text cursor-pointer" @click="openModal"
        >© 2024 . Политика конфиденциальности</span
      >
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    openModal() {
      const modal = document.getElementById("modal");
      if (modal) {
        modal.style.display = "block";
      }
    },
    closeModal() {
      const modal = document.getElementById("modal");
      if (modal) {
        modal.style.display = "none";
      }
    },
  },
};
</script>

<style scoped>
.modal {
  display: none; /* По умолчанию скрыто */
  position: fixed; /* Фиксированное положение */
  top: 0;
  left: 0;
  width: 100%; /* Занимает всю ширину экрана */
  height: 100%; /* Занимает всю высоту экрана */
  background-color: rgba(0, 0, 0, 0.5); /* Затемненный фон */
  z-index: 9999; /* Перекрывает все остальное содержимое */
}

.modal-content {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background-color: #fefefe;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.close {
  position: absolute;
  top: 10px;
  right: 10px;
  cursor: pointer;
}
.secondDiv {
  background: #ffffffcc;
}
.con {
  background: #153138d1;
}
img {
  width: 30px;
}
.mainText {
  font-family: Inter;
  font-size: 38px;
  font-weight: 500;
  line-height: 45.99px;
  text-align: left;
  color: #e3b253;
}

ul {
  list-style: inside;
}

.footer-text {
  font-family: Inter;
  font-size: 20px;
  font-weight: 500;
  line-height: 24.2px;
  color: #ffffff;
}

.footer-text:hover {
  color: #908e8e;
}

@media (max-width: 1024px) {
  .div {
    max-width: 15rem;
    width: 100%;
  }
}
</style>
