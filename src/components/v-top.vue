<template>
  <main>
    <div class="v-top">
      <div class="top-balance">
        <span>Баланс:</span>
        <span>10 000.00 ₽</span>
      </div>
      <ul class="v-top-menu">
        <li><a href="#"><img src="../assets/img/icons/lang.svg" alt=""></a></li>
        <li><a href="#"><img src="../assets/img/icons/settings.svg" alt=""></a></li>
        <li><a href="#"><img src="../assets/img/icons/notifications.svg" alt=""></a></li>
        <li><a href="#"><img src="../assets/img/icons/support.svg" alt=""></a></li>
      </ul>
      <div class="v-user">
        <a href="#" class="">
          <img src="../assets/img/icons/user.svg" alt="">
          <span>Evgeniya@gmail.com</span>
        </a>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: "v-top"
}
</script>

<style scoped>
  main{
    padding-top: 60px;
    max-width: 869px;
    justify-content: space-between;
  }

  .v-top{
    display: flex;
    align-items: center;
  }

  .v-top-menu{
    display: flex;
  }

  .v-top-menu li:not(:last-child) {
    margin-right: 24px;
  }

  .v-user{
    display: flex;
    padding: ;
  }
</style>