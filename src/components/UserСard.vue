<template>
    <div class="conatiner">
      <div class="user-card">
            <h1>Научу зарабатывать от 50 000р. в час</h1>
            <div class="main-information flex">
            <img src="../assets/коуч.jpg" width="500px">
            <div class="info">
                <h2>{{ getAuthorFullName }}</h2>
                <strong>Бизнес-коуч</strong>
                <ul class="list">
                <li>Учу делать РЕАЛЬНЫЕ бабки, на себя просто не хватило времени</li>
                <li>НЕ знаю, что такое "Успешный Успех", но знаю, что нужно ТЕБЕ!</li>
                <li>Пообещал, что побреюсь, когда кого-нибудь ОБМАНУ.</li>
                </ul>
            </div>
            </div>
            <p>Участников: {{ users.length }}</p>
            <ul></ul>
        </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'UserСard',
    data() {
      return {
        firstName: 'Игнатий',
        secondName: 'Иларионович',
        lastName: 'Богатов',
      }
    },
    computed: {
      
    },
}
</script>
  
<style lang="css" scoped>
    .user-card {
      margin-top: 40px;
    }
    .info {
      margin-left: 50px;
    }
    h2 {
      margin-bottom: 14px;
    }
</style>
  