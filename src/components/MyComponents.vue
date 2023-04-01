<template>
    <div class="conatiner">
        <div class="user-card">
            <h1>Научу зарабатывать от 50 000р. в чac</h1>
            <div class="main-information flex">
                <!-- <img src="../assets/коуч.jpg" width="500px" height="500px"> -->
                <div class="info">
                <h2>{{firstName}} {{secondName}} {{lastName}}</h2>
                <strong>Бизнес-коуч</strong>
                <ul class="list">
                    <li>Учу делать РЕАЛЬНЫЕ бабки, на себя просто не хватило времени</li>
                    <li>НЕ знаю, что такое "Успешный Успех", но знаю, что нужно ТЕБЕ!</li>
                    <li>Пообещал, что побреюсь, когда кого-нибудь ОБМАНУ.</li>
                </ul>
                </div>
            </div>
            <p>Участников:</p>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'MyComponents',
        data: () => ({
            firstName: 'Игнатий',
            secondName: 'Иларионович',
            lastName: 'Богатов',
            users: [
                {
                firstName: 'Игнатий',
                secondName: 'Иларионович',
                lastName: 'Богатов'
                },
                {
                firstName: 'Игнатий',
                secondName: 'Иларионович',
                lastName: 'Богатов'
                },
                {
                firstName: 'Игнатий',
                secondName: 'Иларионович',
                lastName: 'Богатов'
                }
            ],
            pages: 3,
            currentPage: 1
        }),
        computed: {
            
        }
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
  .flex {
    display: flex;
  }
</style>
