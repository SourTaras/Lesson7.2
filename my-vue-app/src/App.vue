<template>
  <div>
  <HeaderComponent title="Вітаю у Vue-додатку!" />
  <MessageComponent title="Привіт,Vue" message="Я вмію створювати компоненти із пропсами!" />
  <MessageComponent title="Що далі" message="Тепер я можу передавати різні дані в компоненти!" />
  <BusinessComponent name="Володимир" phone="380929433784" email="example@mail.com" />
  </div>
</template>
<script>
import HeaderComponent from "./components/Header.vue"
import MessageComponent from "./components/MessageComponent.vue"
import BusinessComponent from "./components/Business.vue

export default {
  components: {
    HeaderComponent,
    MessageComponent,
    BusinessComponent
  }
}
</script>

