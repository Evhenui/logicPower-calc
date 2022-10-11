<template>
  <div class="clac">
      <section class="clac__header">
        <div class="clac__header-wrapper">
            <img src="../assets/img/background-gray.png" alt="background imga">
            <div class="clac__header-title-wrapper">
              <h1 class="clac__header-title">Калькулятор подбора АКБ для ИБП</h1>
            </div>
            <img src="../assets/img/Banner-Blog.jpg" alt="background image">
        </div>
      </section>
      <section class="clac__main-information">
        <div class="clac__main-information-wrapper">
          <p class="clac__main-description">С помощью данного калькулятора можно ориентировочно рассчитать необходимую ёмкость аккумулятора для источника бесперебойного питания.</p>
          <section class="calc__source-power">
            <section class="calc__source-header">
              <h3 class="calc__source-power-header-title">Расчет источника бесперебойного питания (расчет ИБП)</h3>
              <button class="calc__source-power-header-button">Подбор ИБП</button>
            </section>
            <section class="calc__source-power-body">

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
          </section>
        </div>
      </section>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class HelloWorld extends Vue {
  
}
</script>

<style scoped lang="scss">

</style>
