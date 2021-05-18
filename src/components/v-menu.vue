<template>
  <nav class="v-menu">
    <div class="v-logo">
      <a href="#"><img src="../assets/img/logo.svg" alt="logo Berty"></a>
    </div>
    <ul class="v-menu-list">
      <li class="v-menu-list-balance">
        <a href="#"><img src="../assets/img/icons/balance.svg" alt="">
          Баланс
        </a>
      </li>
      <ul>
        <li>
          <a href="#"><img src="../assets/img/icons/fill.svg" alt="">
            Пополнить
          </a>
        </li>
        <li>
          <a href="#"><img src="../assets/img/icons/output.svg" alt="">
            Вывод средств
          </a>
        </li>
      </ul>
      <ul>
        <li>
          <a href="#"><img src="../assets/img/icons/story.svg" alt="">
            История
          </a>
        </li>
        <li>
          <a href="#"><img src="../assets/img/icons/templates.svg" alt="">
            Шаблоны
          </a>
        </li>
      </ul>
      <ul>
        <li>
          <a href="#"><img src="../assets/img/icons/shops.svg" alt="">
            Магазины
          </a>
        </li>
        <li>
          <a href="#"><img src="../assets/img/icons/referal.svg" alt="">
            Реферальная программа
          </a>
        </li>
      </ul>
    </ul>
    <div class="apps">
      <a href="#"><img src="../assets/img/icons/applestore.svg" alt=""></a>
      <a href="#"><img src="../assets/img/icons/googleplay.svg" alt=""></a>
    </div>
  </nav>
</template>

<script>
export default {
  name: "v-menu"
}
</script>

<style scoped>
  .v-menu{
    padding-top: 72px;
  }

  .v-menu-list ul:not(:last-child){
    margin-bottom: 48px;
  }

  .v-menu-list ul li:not(:last-child){
    margin-bottom: 30px;
  }

  .v-menu-list li a{
    display: flex;
    align-items: center;
  }

  .v-menu-list ul li img{
    margin-right: 15px;
  }

  .v-menu-list-balance{
    margin-bottom: 48px;
    margin-top: 50px;
    display: flex;
  }

  .v-menu-list-balance img{
    margin-right: 15px;
  }

  .apps{
    display: flex;
    flex-direction: column;
    margin-top: 47px;
  }

  .apps a:first-child{
    margin-bottom: 10px;
  }

</style>