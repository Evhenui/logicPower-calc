<template>
  <div class="calc">
      <div class="calc__wrapper">

        <div class="calc__header">
          <p class="calc__main-description">С помощью данного калькулятора можно ориентировочно рассчитать необходимую ёмкость аккумулятора для источника бесперебойного питания.</p>        
        </div>

        <section class="calc__source-power">
          
          <section class="calc__source-header">
            <h3 class="calc__source-power-header-title">Расчет источника бесперебойного питания (расчет ИБП)</h3>
          </section>

          <section class="calc__source-power-body">
            <form class="calc__source-form" action="">
              <section class="calc__source-power-select">
                <div class="calc__checkbox">
                  <input class="calc__custom-checkbox" type="checkbox" id="line-interactive" name="line-interactive" value="ok">
                  <label class="calc__checkbox-label" for="line-interactive">ИБП линейно интерактивные</label>
                  <div class="calc__checkbox-help">
                      <img src="../assets/icons/help-link.png" alt="help" width="16" height="16">
                    <div class="calc__help-section">
                      <div class="calc__help-section-arrow">
                        <svg width="15" height="18" viewBox="0 0 15 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                          <path d="M-4.37114e-07 9L15 0.339744L15 17.6603L-4.37114e-07 9Z" fill="#F3F3F3"/>
                        </svg>
                      </div>
                      <div class="calc__help-section-wrapper">
                        <p class="calc__help-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. </p>    
                      </div>                     
                    </div>
                  </div>
                </div>
    
                <div class="calc__checkbox">
                  <input class="calc__custom-checkbox" type="checkbox" id="regular-sinusoid" name="regular-sinusoid" value="ok">
                  <label class="calc__checkbox-label" for="regular-sinusoid">ИБП с правильной синусоидой</label>
                  <div class="calc__checkbox-help">
                      <img src="../assets/icons/help-link.png" alt="help" width="16" height="16">
                    <div class="calc__help-section">
                      <div class="calc__help-section-arrow">
                        <svg width="15" height="18" viewBox="0 0 15 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                          <path d="M-4.37114e-07 9L15 0.339744L15 17.6603L-4.37114e-07 9Z" fill="#F3F3F3"/>
                        </svg>
                      </div>
                      <div class="calc__help-section-wrapper">
                        <p class="calc__help-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. </p>    
                      </div>                     
                    </div>
                  </div>
                </div>
    
                <div class="calc__checkbox">
                  <input class="calc__custom-checkbox" type="checkbox" id="smart" name="smart" value="ok">
                  <label class="calc__checkbox-label" for="smart">Smart ИБП Online</label>
                  <div class="calc__checkbox-help">
                      <img src="../assets/icons/help-link.png" alt="help" width="16" height="16">
                    <div class="calc__help-section">
                      <div class="calc__help-section-arrow">
                        <svg width="15" height="18" viewBox="0 0 15 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                          <path d="M-4.37114e-07 9L15 0.339744L15 17.6603L-4.37114e-07 9Z" fill="#F3F3F3"/>
                        </svg>
                      </div>
                      <div class="calc__help-section-wrapper">
                        <p class="calc__help-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. </p>    
                      </div>                     
                    </div>
                  </div>
                </div>
    
                <div class="calc__checkbox">
                  <input class="calc__custom-checkbox" type="checkbox" id="hybrid" name="hybrid" value="ok">
                  <label class="calc__checkbox-label" for="hybrid">ИБП гибридный MPPT с правильной синусоидой</label>
                  <div class="calc__checkbox-help">
                      <img src="../assets/icons/help-link.png" alt="help" width="16" height="16">
                    <div class="calc__help-section">
                      <div class="calc__help-section-arrow">
                        <svg width="15" height="18" viewBox="0 0 15 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                          <path d="M-4.37114e-07 9L15 0.339744L15 17.6603L-4.37114e-07 9Z" fill="#F3F3F3"/>
                        </svg>
                      </div>
                      <div class="calc__help-section-wrapper">
                        <p class="calc__help-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. </p>    
                      </div>                     
                    </div>
                  </div>
                </div>
    
                <div class="calc__checkbox">
                  <input class="calc__custom-checkbox" type="checkbox" id="mppt" name="mppt" value="ok">
                  <label class="calc__checkbox-label" for="mppt">ИБП MPPT с правильной синусоидой</label>
                  <div class="calc__checkbox-help">
                      <img src="../assets/icons/help-link.png" alt="help" width="16" height="16">
                    <div class="calc__help-section">
                      <div class="calc__help-section-arrow">
                        <svg width="15" height="18" viewBox="0 0 15 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                          <path d="M-4.37114e-07 9L15 0.339744L15 17.6603L-4.37114e-07 9Z" fill="#F3F3F3"/>
                        </svg>
                      </div>
                      <div class="calc__help-section-wrapper">
                        <p class="calc__help-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. </p>    
                      </div>                     
                    </div>
                  </div>
                </div>
    
                <div class="calc__checkbox">
                  <input class="calc__custom-checkbox" type="checkbox" id="all" name="all" value="ok">
                  <label class="calc__checkbox-label" for="all">Выбрать все</label>
                </div>
              </section>
              
              <section class="calc__source-power-inputs-enter">

                <div>
                  <h3 class="calc__subtitle source-power">Суммарная мощность приборов, подключаемые к ИБП:</h3>
                  <div class="calc__data-input-wrapper">
                    <input class="calc__data-input" type="number" name="" id="w">
                    <span class="calc__data-input-units">W</span>
                    <div class="calc__input-error">
                      <span class="calc__error">Ошибка: данные некорректны</span>
                    </div>
                  </div>
                </div>

                <div>
                  <h3 class="calc__subtitle source-power">	Необходимая мощность ИБП:</h3>
                  <div class="calc__data-input-general-wrapper">

                    <div class="calc__data-input-wrapper">
                      <input class="calc__data-input" type="number" name="" id="w2">
                      <span class="calc__data-input-units">W</span>
                      <div class="calc__input-error">
                        <span class="calc__error">Ошибка: данные некорректны</span>
                      </div>
                    </div>

                    <div class="calc__data-input-wrapper">
                      <input class="calc__data-input" type="number" name="" id="va">
                      <span class="calc__data-input-units">VA</span>
                      <div class="calc__input-error">
                        <span class="calc__error">Ошибка: данные некорректны</span>
                      </div>
                    </div>

                  </div>
                  
                  
                </div>

                <button class="calc__button-orange">Рассчитать</button>

              </section>
            </form>
            <section class="calc__recommended">
              <h3 class="calc__subtitle orande-title">Рекомендуемые ИБП:</h3>
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

            <form class="calc__form" action="">

              <section class="calc__inputs-wrapper">
                <section class="calc__inputs-enter">
                  <div class="calc__data-input-section">
                  <div class="calc__input-help">
                    <h3 class="calc__subtitle">Мощность ИБП:</h3>
                    <div class="calc__checkbox-help">
                      <img src="../assets/icons/help-link.png" alt="help" width="16" height="16">
                       <div class="calc__help-section">
                      <div class="calc__help-section-arrow">
                        <svg width="15" height="18" viewBox="0 0 15 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                          <path d="M-4.37114e-07 9L15 0.339744L15 17.6603L-4.37114e-07 9Z" fill="#F3F3F3"/>
                        </svg>
                      </div>
                      <div class="calc__help-section-wrapper">
                        <p class="calc__help-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. </p>    
                      </div>                     
                    </div>
                    </div>
                  </div>
                  
                  <div class="calc__data-input-wrapper">
                    <input class="calc__data-input" type="number" name="" id="w">
                    <span class="calc__data-input-units">W</span>
                      <div class="calc__input-error">
                        <span class="calc__error">Ошибка: данные некорректны</span>
                      </div>
                  </div>
                </div>
                
                <div class="calc__data-input-section">
                  <div class="calc__input-help switch">
                    <h3 class="calc__subtitle">	КПД инвертора:</h3>
                    <div class="calc__checkbox-help">
                      <img src="../assets/icons/help-link.png" alt="help" width="16" height="16">
                      <div class="calc__help-section">
                      <div class="calc__help-section-arrow">
                        <svg width="15" height="18" viewBox="0 0 15 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                          <path d="M-4.37114e-07 9L15 0.339744L15 17.6603L-4.37114e-07 9Z" fill="#F3F3F3"/>
                        </svg>
                      </div>
                      <div class="calc__help-section-wrapper">
                        <p class="calc__help-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. </p>    
                      </div>                     
                    </div>
                    </div>
                    <div class="calc__switch-section">
                      <label class="calc__switch-wrapper">
                        <input class="calc__switch-input" type="checkbox">
                        <span class="calc__switch-slider"></span>
                      </label>
                    </div>
                  </div>
                  
                  <div class="calc__data-input-wrapper">
                    <input class="calc__data-input" type="number" name="" id="w">
                    <span class="calc__data-input-units">W</span>
                      <div class="calc__input-error">
                        <span class="calc__error">Ошибка: данные некорректны</span>
                      </div>
                  </div>
                </div>
  
                <div class="calc__data-input-section">
                  <div class="calc__input-help">
                    <h3 class="calc__subtitle">Время работы:</h3>
                  </div>
                  
                  <div class="calc__data-input-wrapper">
                    <input class="calc__data-input" type="number" name="" id="time">
                    <span class="calc__data-input-units">часов</span>
                      <div class="calc__input-error">
                        <span class="calc__error">Ошибка: данные некорректны</span>
                      </div>
                  </div>
                </div>

               <div class="calc__data-input-section">
                  <div class="calc__input-help">
                    <h3 class="calc__subtitle">Номинальное напряжение АКБ:</h3>
                  </div>
                  
                  <div class="calc__data-input-wrapper">
                    <input class="calc__data-input" type="number" name="" id="v">
                    <span class="calc__data-input-units">V</span>
                      <div class="calc__input-error">
                        <span class="calc__error">Ошибка: данные некорректны</span>
                      </div>
                  </div>
                </div>
                </section>

                <button class="calc__button-orange">Рассчитать</button>

              </section>                  

              <div class="calc__data-input-section">
                <h3 class="calc__subtitle source-power">Минимальная ёмкость АКБ:</h3>              
                <div class="calc__data-input-wrapper">
                  <input class="calc__data-input" type="number" name="" id="ah">
                  <span class="calc__data-input-units">Ah</span>
                   <div class="calc__input-error">
                      <span class="calc__error">Ошибка: данные некорректны</span>
                    </div>
                </div>
              </div>

            </form>  
            
            <section class="calc__recommended">
              <h3 class="calc__subtitle orande-title">Рекомендуемые ИБП:</h3>
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

            <form class="calc__form" action="">

              <section class="calc__inputs-wrapper">
                <section class="calc__inputs-enter">
                  <div class="calc__data-input-section">
                  <div class="calc__input-help">
                    <h3 class="calc__subtitle">Нагрузка, W:</h3>
                    <div class="calc__checkbox-help">
                      <img src="../assets/icons/help-link.png" alt="help" width="16" height="16">
                       <div class="calc__help-section">
                      <div class="calc__help-section-arrow">
                        <svg width="15" height="18" viewBox="0 0 15 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                          <path d="M-4.37114e-07 9L15 0.339744L15 17.6603L-4.37114e-07 9Z" fill="#F3F3F3"/>
                        </svg>
                      </div>
                      <div class="calc__help-section-wrapper">
                        <p class="calc__help-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. </p>    
                      </div>                     
                    </div>
                    </div>
                  </div>
                  
                  <div class="calc__data-input-wrapper">
                    <input class="calc__data-input" type="number" name="" id="w">
                    <span class="calc__data-input-units">W</span>
                      <div class="calc__input-error">
                        <span class="calc__error">Ошибка: данные некорректны</span>
                      </div>
                  </div>
                </div>
                
                <div class="calc__data-input-section">
                  <div class="calc__input-help switch">
                    <h3 class="calc__subtitle">КПД инвертора:</h3>
                    <div class="calc__checkbox-help">
                      <img src="../assets/icons/help-link.png" alt="help" width="16" height="16">
                      <div class="calc__help-section">
                      <div class="calc__help-section-arrow">
                        <svg width="15" height="18" viewBox="0 0 15 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                          <path d="M-4.37114e-07 9L15 0.339744L15 17.6603L-4.37114e-07 9Z" fill="#F3F3F3"/>
                        </svg>
                      </div>
                      <div class="calc__help-section-wrapper">
                        <p class="calc__help-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. </p>    
                      </div>                     
                    </div>
                    </div>
                    <div class="calc__switch-section">
                      <label class="calc__switch-wrapper">
                        <input class="calc__switch-input" type="checkbox">
                        <span class="calc__switch-slider"></span>
                      </label>
                    </div>
                  </div>
                  
                  <div class="calc__data-input-wrapper">
                    <input class="calc__data-input" type="number" name="" id="persent">
                    <span class="calc__data-input-units">%</span>
                      <div class="calc__input-error">
                        <span class="calc__error">Ошибка: данные некорректны</span>
                      </div>
                  </div>
                </div>
  
                <div class="calc__data-input-section">
                  <div class="calc__input-help">
                    <h3 class="calc__subtitle">Номинальное напряжение АКБ:</h3>
                  </div>
                  
                  <div class="calc__data-input-wrapper">
                    <input class="calc__data-input" type="number" name="" id="v">
                    <span class="calc__data-input-units">V</span>
                      <div class="calc__input-error">
                        <span class="calc__error">Ошибка: данные некорректны</span>
                      </div>
                  </div>
                </div>

               <div class="calc__data-input-section">
                  <div class="calc__input-help">
                    <h3 class="calc__subtitle">Ёмкость АКБ:</h3>
                  </div>
                  
                  <div class="calc__data-input-wrapper">
                    <input class="calc__data-input" type="number" name="" id="ah">
                    <span class="calc__data-input-units">Ah</span>
                      <div class="calc__input-error">
                        <span class="calc__error">Ошибка: данные некорректны</span>
                      </div>
                  </div>
                </div>
                </section>

                <button class="calc__button-orange">Рассчитать</button>

              </section>                  

              <div class="calc__data-input-section">
                <h3 class="calc__subtitle source-power">Время работы ИБП:</h3>              
                <div class="calc__data-input-wrapper">
                  <input class="calc__data-input" type="number" name="" id="time">
                  <span class="calc__data-input-units">часов</span>
                   <div class="calc__input-error">
                      <span class="calc__error">Ошибка: данные некорректны</span>
                    </div>
                </div>
              </div>

            </form>  
            
            <section class="calc__recommended">
              <h3 class="calc__subtitle orande-title">Рекомендуемые ИБП:</h3>
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
@import './../assets/scss/style.scss';
.calc {
   &__wrapper {
    padding-top: 64px;
    @include width-pad-main();
    margin: 0 auto;
  }

  &__header {
    padding: 32px 0;
    background: var(--color-blue-white);
    box-shadow: 0px 3px 11px rgba(0, 0, 0, 0.2);
    border-radius: 16px;
    margin-bottom: 16px;
  }

  &__main-description {
    @include font($font-size: 20, $line-height: 24, $weight: 600);
    text-align: center;
    color: var(--color-ink-base);
    max-width: 805px;
    width: 100%;
    margin: 0 auto;
  }

  &__inputs-wrapper {
    @include flex-container($direction: column, $spacing: flex-start, $alignment: null);
    row-gap: 56px;
    margin-bottom: 56px;
  }

  &__source-power {
    padding-top: 48px;
  }

  &__source-header {
  }

  &__source-power-header-title {
     text-align: center;
     @include font($font-size: 20, $line-height: 24, $weight: 600);
     text-transform: uppercase;
     color: #2B2B2B;
     margin-bottom: 48px;
  }

  &__source-form {
    @include flex-container($direction: row, $spacing: space-between, $alignment: null);
    margin-bottom: 56px;
  }

  &__checkbox {
    @include flex-container($direction: row, $spacing: null, $alignment: center);
    column-gap: 16px;
  }

  &__custom-checkbox {
      position: absolute;
      z-index: -1;
      opacity: 0;
  }

  &__checkbox-label {
      @include font($font-size: 16, $line-height: 24, $weight: 400);
      display: inline-flex;
      align-items: center;
      user-select: none;
      position: relative;
      &::before {
        transition: all .1s ease-in-out;
        content: '';
        display: inline-block;
        width: 24px;
        height: 24px;
        flex-shrink: 0;
        flex-grow: 0;
        border: 1px solid #CDCFD0;
        border-radius: 50%;
        margin-right: 16px;
      }
      &::after {
        transition: all .1s ease-in-out;
        content: '';
        position: absolute;
        top: 50%;
        left: 8px;
        transform: translateY(-50%);
        width: 8px;
        height: 8px;
        border-radius: 50%;
        background: #FFFFFF;
      }

  }

  &__custom-checkbox:not(:disabled):not(:checked) + &__checkbox-label:hover::before {
      border-color: #E05507;
    }

  &__custom-checkbox:checked + &__checkbox-label::before {
      border-color:#F36C21;
      background-color: #F36C21;
    }

  &__custom-checkbox:disabled + &__checkbox-label::before {
      background-color: #e9ecef;
    }

  &__custom-checkbox {

  }

  &__source-power-body {
    border-bottom: 1px solid #8A8A8A;
    padding-bottom: 48px;
  }

  &__source-power-select {
    @include flex-container($direction: column, $spacing: null, $alignment: null);
    row-gap: 24px;
  }

  &__checkbox-help {
   position: relative;
   cursor: pointer;
  }
  &__checkbox-help:hover &__help-section {
    opacity: 1;
    z-index: 1;
    
  }

  &__help-section {
     top: -20px;
     left: 23px;
     opacity: 0;
     z-index: -1;
     position: absolute;
     transition: all .2s ease-in-out; 
     @include flex-container($direction: row, $spacing: null, $alignment: center);
  }

  &__help-section-wrapper {
     background: #F3F3F3;
     border-radius: 8px;
     padding: 8px;
     width: 267px;
  }

  &__help-description {
    
    @include font($font-size: 12, $line-height: 16, $weight: 400);
    color: #2B2B2B;
  }

  &__source-power-inputs-enter {
    @include flex-container($direction: column, $spacing: null, $alignment: left);
    row-gap: 56px;
    max-width: 678px;
    width: 100%;
  }

  &__data-input-section {
    max-width: 327px;
    width: 100%;
  }

  &__subtitle {
    @include font($font-size: 20, $line-height: 28, $weight: 400);
    color: #2B2B2B;
    &.orande-title {
      @include font($font-size: 20, $line-height: 30, $weight: 600);
      text-transform: uppercase;
      color: #F36C21;
      margin-bottom: 48px;
    }
    &.source-power {
      margin-bottom: 24px;
    }
  }

  &__data-input-wrapper {
    position: relative;
    max-width: 327px;
    width: 100%;
  }

  &__data-input {
    @include font($font-size: 16, $line-height: 16, $weight: 400);
    color: #2B2B2B;
    background: #FFFFFF;
    border: 1px solid #BDBDBD;
    border-radius: 8px;
    width: 100%;
    padding: 16px;
    height: 48px;
    transition: all .1s ease-in-out;
    &::-webkit-outer-spin-button,
    &::-webkit-inner-spin-button {
    -webkit-appearance: none;
    margin: 0;
    }
    &:focus {
      border-color: #8A8A8A;
    }
    &:disabled {
      border-color: #E9E9E9;
      color: #B4B6B8;
    }
  }

  &__input-error {
    transition: all .1s ease-in-out;
    position: absolute;
    bottom: -21px;
    left: 0;
    padding-top: 8px;
    opacity: 0;
  }

  &__data-input-wrapper.active &__input-error {
    opacity: 1;
  }

  &__data-input-wrapper.active &__data-input {
    border-color: #EB1717;
  }

  &__data-input-wrapper.active &__data-input-units {
    border-color: #EB1717;
  }

  &__error {
    @include font($font-size: 12, $line-height: 16, $weight: 400);
    color: #EB1717;
  }

  &__data-input-units {
    transition: all .1s ease-in-out;
    position: absolute;
    top: 0;
    right: 0;
    @include flex-container($direction: row, $spacing: center, $alignment: center);
    width: 87px;
    height: 100%;
    background: #F3F3F3;
    border: 1px solid #BDBDBD;
    border-radius: 8px;
    @include font($font-size: 16, $line-height: 16, $weight: 400);
    color: #2B2B2B;
    &.focus {
      border-color: #8A8A8A;
    }
    &.disabled {
      border-color: #F3F3F3;
      color: #8A8A8A;

    }
  }

  &__button-orange {
    transition: all .1s ease-in-out;
    max-width: 150px;
    width: 100%;
    @include font($font-size: 18, $line-height: 24, $weight: 400);
    color:#FFFFFF;
    background: #F36C21;
    padding: 8px 0;
    text-align: center;
    border-radius: 6px;
    &:hover {
      background: #FF5B00;
    }
    &:active {
      background: #AC450B;
    }
    &:disabled {
      background: #8A8A8A;
    }
  }

  &__data-input-general-wrapper {
    @include flex-container($direction: row, $spacing: null, $alignment: left);
    column-gap: 24px;
  }

  &__recommended {
    text-align: center;
  }

  &__recommended-items {

  }

  &__button-catalog {
    padding: 14.5px 0;
    max-width: 230px;
    width: 100%;
    background: #FFFFFF;
    box-shadow: 0px 3px 11px rgba(0, 0, 0, 0.2);
    border-radius: 36px;
    margin: 0 auto;
    @include flex-container($direction: row, $spacing: center, $alignment: center);
    column-gap: 16px;
  }

  &__button-catalog-name {
    @include font($font-size: 20, $line-height: 28, $weight: 400);
    letter-spacing: 0.02em;
    color: #2B2B2B;
  }

  &__input-help {
     @include flex-container($direction: row, $spacing: null, $alignment: center);
     column-gap: 16px;
     margin-bottom: 24px;
     &.switch {
      margin-bottom: 22px;
     }
  }

  &__inputs-enter {
     @include flex-container($direction: row, $spacing: null, $alignment: baseline);
     gap: 24px;
     flex-wrap: wrap;
     max-width: 1380px;
     width: 100%;
  }

  &__switch-section {
    font-size: 0;
  }

  &__switch-wrapper {
        position: relative;
        display: inline-block;
        width: 56px;
        height: 32px;
      }
      
      &__switch-wrapper &__switch-input {display:none;}
      
      &__switch-slider {
        position: absolute;
        cursor: pointer;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background: #E3E5E6;
        border-radius: 32px;
        transition: all .2s ease-in-out;
        &::before {
            position: absolute;
            content: "";
            height: 28px;
            width: 28px;
            left: 2px;
            bottom: 2px;
            background-color: #FFFFFF;
            border-radius: 50%;
            transition: all .2s ease-in-out;
        }
      }
      
      &__switch-input:checked + &__switch-slider{
        background: #F36C21;
      }

      &__switch-input:checked + &__switch-slider:active{
        background: #E05507;
      }

      &__switch-input + &__switch-slider:active{
        background: #E05507;
      }
      
      &__switch-input:checked + &__switch-slider:before {
        transform: translateX(24px);
      }

  &__switch {
  }

  &__switch-input {
  }

  &__switch-slider {
  }

  &__about-selected {
  }

  &__about-selected-item {
  }

  &__about-section {
  }

  &__about-title {
  }

  &__about-description {
  }

  &__about-offer {
  }

  &__about-list {
  }

  &__about-list-item {
  }

  &__list-num {
  }

  &__list-text {
  }

  &__item-icon {
  }
}

</style>
