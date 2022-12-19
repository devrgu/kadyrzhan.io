<template>
    <div class="conque">
        <div class="conque-content content">
          <div class="conque-title sections-title title subtitle">
           <h2>Почему вы должны мне<br>доверять?</h2>
           <p>Я знаю всю эту боль изнутри. Я знаю, как пройти через это. Я понимаю и чувствую вас в деталях. Я на собственном опыте убедился, что гипнотерапия - инструмент позволяющий, вытащить человека с нищеты, обрести прочную любовь, вылечить его от любых болезней и получить крепкое здоровье. Обратитесь ко мне на консультацию.</p>
       </div>
           <div class="conque-wrap">
            <div class="conque-card-1 conque-card">
                <div class="conque-card-1-icon conque-card-icon">
                   <iconpobeditel  width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg"/>
                </div>
                <div class="conque-card-1-text conque-card-text">
                    <div class="conque-card-1-title conque-card-title">
                        <h3>Будете здоровы и любимы</h3>
                    </div>
                    <div class="conque-card-1-information conque-card-information information">
                        <p>Я знаю всю эту боль на своем опыте. Я знаю, как пройти через это. Я полностью понимаю и чувствую вас. Я на собственном опыте убедился, что гипнотерапия может снова разжечь огонь любви и оставить холодность и непонимание в прошлом.</p>
                    </div>
                </div>
            </div>
            <div class="conque-card-1 conque-card">
                <div class="conque-card-1-icon conque-card-icon">
                    <iconpobeditel  width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg"/>
                </div>
                <div class="conque-card-1-text conque-card-text">
                    <div class="conque-card-1-title conque-card-title">
                        <h3>Возврат обретения
новой жизни

</h3>
                    </div>
                    <div class="conque-card-1-information conque-card-information information">
                        <p>У вас снова загорится желание жить, вы будете полны амбиций.</p>
                    </div>
                </div>
            </div>
            <div class="conque-card-1 conque-card">
                <div class="conque-card-1-icon conque-card-icon">
                    <iconpobeditel  width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg"/>
                </div>
                <div class="conque-card-1-text conque-card-text">
                    <div class="conque-card-1-title conque-card-title">
                        <h3>Исчезнет тревога, вы обретете покой души</h3>
                    </div>
                    <div class="conque-card-1-information conque-card-information information">
                        <p>Вы забудете о конфликтах, язвительных замечаниях и взаимной раздраженности</p>
                    </div>
                </div>
            </div>
            <div class="conque-card-1 conque-card">
                <div class="conque-card-1-icon conque-card-icon">
                    <iconpobeditel  width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg"/>
                </div>
                <div class="conque-card-1-text conque-card-text">
                    <div class="conque-card-1-title conque-card-title">
                        <h3>Все пойдет по
плану процветания</h3>
                    </div>
                    <div class="conque-card-1-information conque-card-information information">
                        <p>Вы почувствуете, что все в жизни складывается именно так, как вы всегда мечтали.</p>
                    </div>
                </div>
            </div>
            <div class="conque-card-1 conque-card">
                <div class="conque-card-1-icon conque-card-icon">
                    <iconpobeditel  width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg"/>
                </div>
                <div class="conque-card-1-text conque-card-text">
                    <div class="conque-card-1-title conque-card-title">
                        <h3>Думайте верно и
правильно</h3>
                    </div>
                    <div class="conque-card-1-information conque-card-information information">
                        <p>Это инструмент для концентраций подсознания, с которой можно изменить свои убеждения в лучшую сторону.</p>
                    </div>
                </div>
            </div>
            <div class="conque-card-1 conque-card">
                <div class="conque-card-1-icon conque-card-icon">
                    <iconpobeditel  width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg"/>
                </div>
                <div class="conque-card-1-text conque-card-text">
                    <div class="conque-card-1-title conque-card-title">
                        <h3>Будьте тем кем
вы хотели быть</h3>
                    </div>
                    <div class="conque-card-1-information conque-card-information information">
                        <p>На консультаций я вам это докажу. Для нас это обычное дело, но люди называют это чудом</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
</template>
<script>
import iconpobeditel from '~/assets/img/iconpobeditel.svg?inline';

export default {
  components: {
    iconpobeditel
  }
}
</script>
<style>
    .conque{
        background-color: #f5f5f5;
        padding: 90px 10px;
    }
    .conque-wrap{
        padding-top: 90px;
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
    }
    .conque-title{
        text-align: left !important;
        margin: 0 !important;
        width: auto!important;
    }
    .conque-title h2{
        padding-bottom: 32px;
    }
    .conque-card{
        width: 320px;
        min-height: 307px;
        border-style: solid;
        border-width: 0px 0px 3px 0px;
        border-color: #41cb52;
        border-radius: 5px 5px 5px 5px;
        background-color: #FFFFFF;
        padding: 40px 20px 40px 30px;
        box-sizing: content-box;
        margin: 0 10px 20px 10px;
    }
    .conque-card-icon {
        background-color: #41cb52;
        border-radius: 100% 100% 100% 100%;
        text-align: center;
        height: 95px;
        width: 95px;
        display: flex;
        align-items: center;
        justify-content: center;
        margin-bottom: 25px;
    }
    .conque-card-icon svg{
        width: 50px;
    }
    .conque-card-icon svg path{
        fill: #FFFFFF !important;
    }
    .conque-card-title h3{
        font-size: 20px;
        margin: 0 0 15px 0;
        font-size: 20px;
        color: #232323;
        text-transform: uppercase;
    }
    .conque-card-information{
        margin-bottom: 1rem;
        font-size: 16px !important;
        font-weight: 500;
    }
</style>