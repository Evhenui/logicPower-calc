<template>
  <div class="clac">
      <div class="clac__wrapper">

        <div class="clac__header">
          <p class="clac__main-description">С помощью данного калькулятора можно ориентировочно рассчитать необходимую ёмкость аккумулятора для источника бесперебойного питания.</p>        
        </div>

        <section class="calc__source-power">
          
          <section class="calc__source-header">
            <h3 class="calc__source-power-header-title">Расчет источника бесперебойного питания (расчет ИБП)</h3>
          </section>

          <section class="calc__source-power-body">
            <form action="">
              <section class="calc__source-power-select">
                <div class="checkbox">
                  <input class="custom-checkbox" type="checkbox" id="color-1" name="color-1" value="indigo">
                  <label for="color-1">ИБП линейно интерактивные</label>
                  <div class="calc__checkbox-help">
                    <img src="../assets/icons/help-link.png" alt="help" width="16" height="16">
                    <div class="calc__help-section">
                      <p class="calc__help-description">Обеспечивают кратковременное резервное питание оборудования, и выполняет функции стабилизатора напряжения в сети.</p>
                    </div>
                  </div>
                </div>
    
                <div class="checkbox">
                  <input class="custom-checkbox" type="checkbox" id="color-1" name="color-1" value="indigo">
                  <label for="color-1">ИБП с правильной синусоидой</label>
                  <div class="calc__checkbox-help">
                    <img src="../assets/icons/help-link.png" alt="help" width="16" height="16">
                    <div class="calc__help-section">
                      <p class="calc__help-description">Обеспечивают кратковременное резервное питание оборудования, и выполняет функции стабилизатора напряжения в сети.</p>
                    </div>
                  </div>
                </div>
    
                <div class="checkbox">
                  <input class="custom-checkbox" type="checkbox" id="color-1" name="color-1" value="indigo">
                  <label for="color-1">Smart ИБП Online</label>
                  <div class="calc__checkbox-help">
                    <img src="../assets/icons/help-link.png" alt="help" width="16" height="16">
                    <div class="calc__help-section">
                      <p class="calc__help-description">Обеспечивают кратковременное резервное питание оборудования, и выполняет функции стабилизатора напряжения в сети.</p>
                    </div>
                  </div>
                </div>
    
                <div class="checkbox">
                  <input class="custom-checkbox" type="checkbox" id="color-1" name="color-1" value="indigo">
                  <label for="color-1">ИБП гибридный MPPT с правильной синусоидой</label>
                  <div class="calc__checkbox-help">
                    <img src="../assets/icons/help-link.png" alt="help" width="16" height="16">
                    <div class="calc__help-section">
                      <p class="calc__help-description">Обеспечивают кратковременное резервное питание оборудования, и выполняет функции стабилизатора напряжения в сети.</p>
                    </div>
                  </div>
                </div>
    
                <div class="checkbox">
                  <input class="custom-checkbox" type="checkbox" id="color-1" name="color-1" value="indigo">
                  <label for="color-1">ИБП MPPT с правильной синусоидой</label>
                  <div class="calc__checkbox-help">
                    <img src="../assets/icons/help-link.png" alt="help" width="16" height="16">
                    <div class="calc__help-section">
                      <p class="calc__help-description">Обеспечивают кратковременное резервное питание оборудования, и выполняет функции стабилизатора напряжения в сети.</p>
                    </div>
                  </div>
                </div>
    
                <div class="checkbox">
                  <input class="custom-checkbox" type="checkbox" id="color-1" name="color-1" value="indigo">
                  <label for="color-1">Выбрать все</label>
                </div>
              </section>
              
              <section class="calc__source-power-inputs-enter">

                <div class="calc__data-input-section">
                  <h3 class="calc__subtitle">Суммарная мощность приборов, подключаемые к ИБП:</h3>
                  <div class="calc__data-input-wrapper">
                    <input class="calc__data-input" type="number" name="" id="w">
                    <span class="calc__data-input-units">W</span>
                  </div>
                  <button class="calc__button-orange">Рассчитать</button>
                </div>

                <div class="calc__data-input-section">
                  <h3 class="calc__subtitle">	Необходимая мощность ИБП:</h3>
                  <div class="calc__data-input-general-wrapper">

                    <div class="calc__data-input-wrapper">
                      <input class="calc__data-input" type="number" name="" id="w2">
                      <span class="calc__data-input-units">W</span>
                    </div>

                    <div class="calc__data-input-wrapper">
                      <input class="calc__data-input" type="number" name="" id="va">
                      <span class="calc__data-input-units">VA</span>
                    </div>

                  </div>
                  
                  <button class="calc__button-orange">Рассчитать</button>
                </div>

              </section>
            </form>
            <section class="calc__recommended">
              <h3 class="calc__subtitle">Рекомендуемые ИБП:</h3>
              <section class="calc__recommended-items">

              </section>
              <button class="calc__button-catalog">
                <svg width="21" height="22" viewBox="0 0 21 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M7.83813 2.9162H1V9.75432H7.83813V2.9162Z" stroke="#8A8A8A" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                  <path d="M18.5838 13.6618H11.7456V20.5H18.5838V13.6618Z" stroke="#8A8A8A" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                  <path d="M7.83813 13.6618H1V20.5H7.83813V13.6618Z" stroke="#8A8A8A" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                  <path d="M15.1646 1.49998L10.3293 6.33527L15.1646 11.1706L19.9999 6.33527L15.1646 1.49998Z" stroke="#8A8A8A" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
                <span class="calc__button-catalog-name">В каталог</span>
              </button>
            </section>

          </section>

        </section>

        <section class="calc__source-power">

          <section class="calc__source-header">
            <h3 class="calc__source-power-header-title">Расчет емкости аккумуляторной батареи для источника бесперебойного питания</h3>
          </section>

          <section class="calc__source-power-body">

            <form action="">

              <section class="clac__inputs-wrapper">

                <div class="calc__data-input-section">
                  <div class="calc__input-help">
                    <h3 class="calc__subtitle">Мощность ИБП:</h3>
                    <div class="calc__checkbox-help">
                      <img src="../assets/icons/help-link.png" alt="help" width="16" height="16">
                      <div class="calc__help-section">
                        <p class="calc__help-description">Отлично справляются с обеспечением резервного питания систем видеонаблюдения, котлов отопления и другой техники</p>
                      </div>
                    </div>
                  </div>
                  
                  <div class="calc__data-input-wrapper">
                    <input class="calc__data-input" type="number" name="" id="w">
                    <span class="calc__data-input-units">W</span>
                  </div>
                </div>
                
                <div class="calc__data-input-section">
                  <div class="calc__input-help">
                    <h3 class="calc__subtitle">	КПД инвертора:</h3>
                    <div class="calc__checkbox-help">
                      <img src="../assets/icons/help-link.png" alt="help" width="16" height="16">
                      <div class="calc__help-section">
                        <p class="calc__help-description">Отлично справляются с обеспечением резервного питания систем видеонаблюдения, котлов отопления и другой техники</p>
                      </div>
                    </div>
                    <div class="calc__switch-wrapper">
                      <label class="calc__switch">
                        <input class="calc__switch-input" type="checkbox">
                        <span class="calc__switch-slider"></span>
                      </label>
                    </div>
                  </div>
                  
                  <div class="calc__data-input-wrapper">
                    <input class="calc__data-input" type="number" name="" id="w">
                    <span class="calc__data-input-units">W</span>
                  </div>
                </div>
  
                <div class="calc__data-input-section">
                  <div class="calc__input-help">
                    <h3 class="calc__subtitle">Время работы:</h3>
                  </div>
                  
                  <div class="calc__data-input-wrapper">
                    <input class="calc__data-input" type="number" name="" id="time">
                    <span class="calc__data-input-units">часов</span>
                  </div>
                </div>

                <div class="calc__data-input-section">
                  <h3 class="calc__subtitle">Номинальное напряжение АКБ:</h3>              
                  <div class="calc__data-input-wrapper">
                    <input class="calc__data-input" type="number" name="" id="v">
                    <span class="calc__data-input-units">V</span>
                  </div>
                </div>

                <button class="calc__button-orange">Рассчитать</button>

              </section>                  

              <div class="calc__data-input-section">
                <h3 class="calc__subtitle">Минимальная ёмкость АКБ:</h3>              
                <div class="calc__data-input-wrapper">
                  <input class="calc__data-input" type="number" name="" id="ah">
                  <span class="calc__data-input-units">Ah</span>
                </div>
              </div>

            </form>  
            
            <section class="calc__recommended">
              <h3 class="calc__subtitle">Рекомендуемые АКБ:</h3>
              <section class="calc__recommended-items">

              </section>
              <button class="calc__button-catalog">
                <svg width="21" height="22" viewBox="0 0 21 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M7.83813 2.9162H1V9.75432H7.83813V2.9162Z" stroke="#8A8A8A" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                  <path d="M18.5838 13.6618H11.7456V20.5H18.5838V13.6618Z" stroke="#8A8A8A" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                  <path d="M7.83813 13.6618H1V20.5H7.83813V13.6618Z" stroke="#8A8A8A" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                  <path d="M15.1646 1.49998L10.3293 6.33527L15.1646 11.1706L19.9999 6.33527L15.1646 1.49998Z" stroke="#8A8A8A" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
                <span class="calc__button-catalog-name">В каталог</span>
              </button>
            </section>
            
          </section>
        </section>

        <section class="calc__source-power">

          <section class="calc__source-header">
            <h3 class="calc__source-power-header-title">Расчет времени автономной работы ИБП</h3>
          </section>

          <section class="calc__source-power-body">

            <form action="">

              <section class="clac__inputs-wrapper">

                <div class="calc__data-input-section">
                  <div class="calc__input-help">
                    <h3 class="calc__subtitle">Нагрузка, W:</h3>
                    <div class="calc__checkbox-help">
                      <img src="../assets/icons/help-link.png" alt="help" width="16" height="16">
                      <div class="calc__help-section">
                        <p class="calc__help-description">Отлично справляются с обеспечением резервного питания систем видеонаблюдения, котлов отопления и другой техники</p>
                      </div>
                    </div>
                  </div>
                  
                  <div class="calc__data-input-wrapper">
                    <input class="calc__data-input" type="number" name="" id="w">
                    <span class="calc__data-input-units">W</span>
                  </div>
                </div>
                
                <div class="calc__data-input-section">
                  <div class="calc__input-help">
                    <h3 class="calc__subtitle">КПД инвертора:</h3>
                    <div class="calc__checkbox-help">
                      <img src="../assets/icons/help-link.png" alt="help" width="16" height="16">
                      <div class="calc__help-section">
                        <p class="calc__help-description">Отлично справляются с обеспечением резервного питания систем видеонаблюдения, котлов отопления и другой техники</p>
                      </div>
                    </div>
                    <div class="calc__switch-wrapper">
                      <label class="calc__switch">
                        <input class="calc__switch-input" type="checkbox">
                        <span class="calc__switch-slider"></span>
                      </label>
                    </div>
                  </div>
                  
                  <div class="calc__data-input-wrapper">
                    <input class="calc__data-input" type="number" name="" id="w">
                    <span class="calc__data-input-units">W</span>
                  </div>
                </div>
  
                <div class="calc__data-input-section">
                  <div class="calc__input-help">
                    <h3 class="calc__subtitle">Номинальное напряжение АКБ:</h3>
                  </div>
                  
                  <div class="calc__data-input-wrapper">
                    <input class="calc__data-input" type="number" name="" id="v">
                    <span class="calc__data-input-units">V</span>
                  </div>
                </div>

                <div class="calc__data-input-section">
                  <h3 class="calc__subtitle">Ёмкость АКБ:</h3>              
                  <div class="calc__data-input-wrapper">
                    <input class="calc__data-input" type="number" name="" id="ah">
                    <span class="calc__data-input-units">ah</span>
                  </div>
                </div>

                <button class="calc__button-orange">Рассчитать</button>

              </section>                  

              <div class="calc__data-input-section">
                <h3 class="calc__subtitle">Время работы ИБП:</h3>              
                <div class="calc__data-input-wrapper">
                  <input class="calc__data-input" type="number" name="" id="time">
                  <span class="calc__data-input-units">часов</span>
                </div>
              </div>

            </form>  
            
            <section class="calc__recommended">
              <h3 class="calc__subtitle">Рекомендуемые АКБ:</h3>
              <section class="calc__recommended-items">

              </section>
              <button class="calc__button-catalog">
                <svg width="21" height="22" viewBox="0 0 21 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M7.83813 2.9162H1V9.75432H7.83813V2.9162Z" stroke="#8A8A8A" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                  <path d="M18.5838 13.6618H11.7456V20.5H18.5838V13.6618Z" stroke="#8A8A8A" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                  <path d="M7.83813 13.6618H1V20.5H7.83813V13.6618Z" stroke="#8A8A8A" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                  <path d="M15.1646 1.49998L10.3293 6.33527L15.1646 11.1706L19.9999 6.33527L15.1646 1.49998Z" stroke="#8A8A8A" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
                <span class="calc__button-catalog-name">В каталог</span>
              </button>
            </section>
            
          </section>
        </section>

        <section class="calc__about-selected">
          <a class="calc__about-selected-item" href="#">Описание UPS 500VA + литиевая (LiFePO4) батарея 750W</a>
          <section class="calc__about-section">
            <h1 class="calc__about-title">Комплект видеонаблюдения для квартиры на 2 камеры</h1>
            <p class="calc__about-description">Готовые комплекты видеонаблюдения на 2 камеры в одной коробке. Комплекты видеонаблюдения GreenVision бюджетное решение для квартиры, небольшого офиса или дачи.</p>
            <h3 class="calc__about-offer">Купить комплект видеонаблюдения на 2 камеры в Украине: почему это выгодно?</h3>
            <ul class="calc__about-list">
              <li class="calc__about-list-item"> 
                <span class="calc__list-num">1</span> 
                <span class="calc__list-text">Стоимость комплекта на 15-20% (зависит от модели) ниже общих затрат, если вы решите приобретать оборудование для системы видеонаблюдения по отдельности.</span>
              </li>
              <li class="calc__about-list-item"> 
                <span class="calc__list-num">2</span> 
                <span class="calc__list-text">100% совместимость всех элементов видеонаблюдения, входящих в комплект, что существенно экономит вам время на поиски необходимого оборудования.</span>
              </li>
              <li class="calc__about-list-item"> 
                <span class="calc__list-num">3</span> 
                <span class="calc__list-text">Возможность установить систему видеонаблюдения своими руками. В комплектацию входят все материалы и приспособления, необходимые для подключения и монтажа.</span>
              </li>
              <li class="calc__about-list-item"> 
                <span class="calc__list-num">4</span> 
                <span class="calc__list-text">Простые и интуитивные настройки системы видеонаблюдения, встроенные в меню регистратора. Интерфейс доступен на нескольких языках.</span>
              </li>
              <li class="calc__about-list-item"> 
                <span class="calc__list-num">5</span> 
                <span class="calc__list-text">Бесплатное программное обеспечение и приложения для удаленного доступа. ПО и обновления к нему можно скачать на официальном сайте компании GreenVision</span>
              </li>
            </ul>
          </section>
          
          <section class="calc__about-section">
            <h1 class="calc__about-title">Для чего нужны системы видеонаблюдения на 2 камеры?</h1>
            <p class="calc__about-description">Две камеры видеонаблюдения для квартиры &ndash; это много или мало? Все зависит от объектов, которые вы планируете контролировать.&nbsp;</p>
            <p class="calc__about-description">Установите одну камеру видеонаблюдения возле входной двери, обеспечив, таким образом, полный контроль безопасности входа в квартиру (дом, офис, небольшой магазин и т.д.)</p>
            <h3 class="calc__about-offer">Другую камеру видеонаблюдения можно установить:</h3>
            <ul class="calc__about-list">
              <li class="calc__about-list-item"> 
                <span class="calc__item-icon"></span> 
                <span class="calc__list-text">в помещении, где хранятся материальные ценности;</span>
              </li>
              <li class="calc__about-list-item"> 
                <span class="calc__item-icon"></span> 
                <span class="calc__list-text">в детской, если есть необходимость контроля работы няни</span>
              </li>
              <li class="calc__about-list-item"> 
                <span class="calc__item-icon"></span> 
                <span class="calc__list-text">в коридоре, если нужно контролировать перемещение по квартире</span>
              </li>
              <li class="calc__about-list-item"> 
                <span class="calc__item-icon"></span> 
                <span class="calc__list-text">или в любом другом месте, которое вы хотите держать под контролем</span>
              </li>
            </ul>
          </section>

          <section class="calc__about-section">
            <h1 class="calc__about-title">Функциональные возможности систем видеонаблюдения: видеорегистратор + 2 камеры</h1>
            <p class="calc__about-description">Высокое качество изображения. (IP, гибридные,Wi-Fi) камеры, которые входят в комплект видеонаблюдения, имеют разрешение изображения (2,3,5)МП. Вы сможете просматривать видео и сохранять изображение с высокой степенью детализации.</p>          
          </section>
        </section>
      </div>  
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class Calc extends Vue {
  
}
</script>

<style lang="scss">
@import '../_shared/assets/scss/abstract/mixin';
.clac {
  max-width: 1920px;
  margin-left: auto;
  margin-right: auto;
  &__header {
    margin-bottom: 40px;
  }

  &__header-wrapper {
    position: relative;
    background-image: url('../assets/img/Banner-Blog.jpg');
    background-repeat: no-repeat;
    background-position: right top;
  }

  &__header-title-wrapper {
    position: absolute;
    top: 197px;
    left: 185px;
  }

  &__header-title {
   @include font($font-size: 48, $line-height: 52, $weight: 700);
   max-width: 550px;
   width: 100%;
   color: var(--color-ink-lighter);
  }

  &__main-information {
  }

  &__main-information-wrapper {
  }

  &__main-description {
   margin: 0 auto 40px auto;
   @include font($font-size: 18, $line-height: 24, $weight: 400);
   text-align: center;
   max-width: 1116px;
   width: 100%;
   color: var(--color-ink-base);
  }

  &__inputs-wrapper {
  }
}
.calc {

  &__source-power {
  }

  &__source-header {
  }

  &__source-power-header-title {
  }

  &__button-orange {
  }

  &__source-power-body {
  }

  &__checkbox-help {
  }

  &__help-section {
  }

  &__help-description {
  }

  &__data-input-section {
  }

  &__subtitle {
  }

  &__data-input-wrapper {
  }

  &__data-input {
  }

  &__data-input-units {
  }

  &__data-input-general-wrapper {
  }

  &__recommended {
  }

  &__recommended-items {
  }

  &__button-catalog {
  }

  &__button-catalog-name {
  }

  &__input-help {
  }

  &__switch-wrapper {
  }

  &__switch {
  }

  &__switch-input {
  }

  &__switch-slider {
  }

  &__about {
  }

  &__about-description {
  }
}
.checkbox {
}
.custom-checkbox {
}

</style>
