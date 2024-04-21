<template>
  <div class="app-store">

    <div class="app-store1">
      <h3>Юридическая информация</h3>
      <h3>ООО АВТОРУСЬН </h3>
      <h3>ИНН5036130725 / ОГРН1135074006022</h3>
      <h3>Юридический адрес: 142111, Московскаяобл, Подольскг,</h3>
      <h3>ЮныхЛенинцевпр-кт, дом№1 </h3>
      <h3>Тел./факс: +7(495)276-87-77</h3>

    </div>

    <div class="app-store2">

      <div class="app-store2-2">

        <div class="app-store2-items1">

          <div class="app-store2-item1">
            <i class="fa-brands fa-vk"></i>
          </div>

          <div class="app-store2-item1">
            <i class="fa-brands fa-telegram"></i>
          </div>

          <div class="app-store2-item1">
            <i class="fa-brands fa-odnoklassniki"></i>
          </div>
        </div>

        <div class="app-store2-items2">

          <div class="app-store2-item2">
            <i class="fa-brands fa-apple"></i>

            <div class="app-store2-item2-div">
              <span>Доступно в</span>
              <h2>App Store</h2>
            </div>
          </div>

          <div class="app-store2-item2">
            <i class="fa-brands fa-google-play"></i>

            <div class="app-store2-item2-div">
              <span>Доступно в</span>
              <h2>Google Play</h2>
            </div>
          </div>

        </div>

      </div>

      <div class="app-store-item3">
        <img class="app-store-item3-img"
             src="https://s3-alpha-sig.figma.com/img/7234/65aa/3c787aa8fd33a172c99dd25052ecf150?Expires=1714348800&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=fsXE6nOnm0bqOc0wQdRgD52RfFPX3Olc2yhNGdcM-q4H~vKSSKxisXzIw-q8~jyxcewl6dlYyyV9gTuN~Agwb8lBU1RTtHZKOVmKHwqj-EiXaYVa7BCG6LqSXFJY~59graagI~t0Wwq3ns31PWwxg5idwE8~K4jsAODDEUSAEpxAOEF-FXnYJWLcVMi7LGClBY4kqSLuO5H8FKHNYzKvpsXmZpfqovzeULqb4zOz80Bli8Iz~xx6Zyy1-iKMfP9D9chkYnL212ebhlC-2QH9ODUaclhfNmSjLH7c3J7y4i-7ySAyFco4s4GjGQ2Ois6L~gLKrko~gJv4VMHpX2Rgug__"
             alt="">
      </div>

    </div>

    <hr class="app-store-hr">

    <div class="app-store3">
      <h2>Подробнее об условиях акции ></h2>
      <p>*Стоимость автомобилей указана в базовой комплектации.Максимальная выгода достигается за счет скидки на модели
        HAVAL при покупке автомобиля по программе Trade-in и кредит с учетом дополнительной выгоды от дилерских центров
        HAVAL Авторусь Подольск и HAVAL Авторусь Лосиный Остров. Подробности спецпредложения в отделе продаж ООО
        «АВТОРУСЬ Н». Данный интернет-сайт носит информационный характер и не является публичной офертой, определяемой
        положениями Статьи 437 ГК РФ. Для получения подробной информации обращайтесь в официальный дилерский центр
        автомобилей Haval ООО «АВТОРУСЬ Н» или по телефону: +7 (495) 032-52-97. Специальное предложение действует на
        покупку нового автомобиля с 01.11.2023 по 29.02.2024. ** Предложение по тарифному плану «Оптимальный»
        распространяется на новые автомобили Бренда HAVAL модели JOLION, М6, F7, F7x, DARGO, H9. Указанная процентная
        ставка по кредиту 0,01% годовых достигается при следующих условиях кредитования: первоначальный взнос от 60% и
        не более 90% от стоимости автомобиля, сумма кредита от 100 000 руб. до 6 000 000 руб., срок кредитования 12 мес.
        Условия по кредиту и тарифы могут быть изменены Банком в одностороннем порядке. Банк вправе отказать в выдаче
        автокредита. Обеспечение по кредиту — залог приобретаемого автомобиля. Страхование по КАСКО HAVAL Insurance.
        Условия кредитования актуальны на 01.09.2023 г., подробнее уточняйте в официальных дилерских центрах HAVAL.
        Предложение носит информационный характер, не является публичной офертой. Кредит предоставляется ООО «Драйв Клик
        Банк» ИНН 6452010742, ОГРН 1027739664260, место нахождения: 125124 г. Москва, ул. Правды, д. 26. Лицензия Банка
        России № 2168 (бессрочная) от 09.12.2022.</p>
      <h3>Этот сайт защищен reCAPTCHA, и к нему применяются политика конфиденциальности Google и условия предоставления
        услуг</h3>
    </div>

  </div>
</template>

<script lang="ts">
export default {
  name: "app-store",
  props: [],
  setup(props: any) {

    return {}
  }
}
</script>

<style lang="scss">
.app-store {
  width: 100%;
  display: flex;
  justify-content: space-around;
  background: var(--app-black);
  margin-top: 100px;
  flex-wrap: wrap;
  padding: 15px;
}

.app-store1 {
  width: 50%;
  padding: 10px;
  color: white;
}

.app-store2 {
  width: 50%;
  padding: 10px;
  color: white;
  display: flex;
  justify-content: flex-end;
  align-items: flex-start;
}

.app-store2-items1 {
  display: flex;
  justify-content: space-around;
}

.app-store2-item1 {
  width: 60px;
  height: 60px;
  border-radius: 50%;
  font-size: 35px;
  background: var(--app-aquamarine);
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.app-store2-items2 {
  display: flex;
}

.app-store2-item2 {
  width: 220px;
  border: 1px solid var(--app-white);
  color: var(--app-white);
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 15px;

  i {
    font-size: 50px;
  }
}

.app-store2-item2-div {
  margin-bottom: 10px;
  margin-left: 10px;

  h2 {
    margin-bottom: 0;
    margin-top: 10px;
  }
}

.app-store-item3-img {
  width: 145px;
}

.app-store-hr {
  width: 100%;
  border: 2px solid var(--app-white);
  margin-top: 30px;
}

.app-store3 {
  width: 100%;
  margin-top: 80px;
  color: white;
}

@media only screen and (max-width: 620px) {
  .app-store {
    width: 100%;
    display: flex;
    justify-content: flex-start;
    align-items: flex-start;
    flex-direction: column;
    margin-top: 50px;
  }
  .app-store1 {
    width: 100%;
  }
  .app-store2 {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0;

  }
  .app-store2-2 {
    width: 50%;
    display: flex;
    justify-content: flex-start;
    align-items: flex-start;
    flex-direction: column;
    padding: 5px;
  }
  .app-store-item3{
    width: 50%;
    display: flex;
    justify-content: flex-end;
  }
  .app-store-item3-img{
    width: 95%;
  }
  .app-store2-items2{
    display: flex;
    justify-content: flex-end;
    align-items: flex-end;
    flex-direction: column;
  }
  .app-store2-item1{
    margin: 10px;
  }
}
</style>