<template>
<div class="whyme">
   <div class="whyme-title sections-title title">
       <h2>Я помогаю вам придти к <br>лучшей жизни!</h2>
       <div class="hr-center">
           <hr>
       </div>
       <p>
В программе лечения вы:</p>
   </div>
    <div class="whyme-content content">
        <div class="reason-1 reason">
            <div class="reason-1-icon reason-icon">
                <iconpobeditel loading="lazy" width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg"/>
            </div>
            <div class="reason-1-text reason-text">
                <div class="reason-1-title reason-title">
                    <h3>Будете здоровы и любимы</h3>
                </div>
                <div class="reason-1-information reason-information information">
                    <p>Вы будете здоровы и с благодарностью принимать любовь близкого человека.</p>
                </div>
            </div>
        </div>
        <div class="reason-1 reason">
            <div class="reason-1-icon reason-icon">
            <iconpobeditel loading="lazy" width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg"/>
            </div>
            <div class="reason-1-text reason-text">
                <div class="reason-1-title reason-title">
                    <h3>Возврат обретения новой жизни</h3>
                </div>
                <div class="reason-1-information reason-information information">
                    <p>У вас снова загорится желание жить, вы будете полны амбиций.</p>
                </div>
            </div>
        </div>
        <div class="reason-1 reason">
            <div class="reason-1-icon reason-icon">
        <iconpobeditel loading="lazy" width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg"/>
            </div>
            <div class="reason-1-text reason-text">
                <div class="reason-1-title reason-title">
                    <h3>Обретете покой души</h3>
                </div>
                <div class="reason-1-information reason-information information">
                    <p>Вы забудете о конфликтах, язвительных замечаниях и взаимной раздраженности.</p>
                </div>
            </div>
        </div>
        <div class="reason-1 reason">
            <div class="reason-1-icon reason-icon">
                 <iconpobeditel loading="lazy" width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg"/>
            </div>
            <div class="reason-1-text reason-text">
                <div class="reason-1-title reason-title">
                    <h3>Все пойдет по плану процветания</h3>
                </div>
                <div class="reason-1-information reason-information information">
                    <p>Вы почувствуете, что все в жизни складывается именно так, как вы всегда мечтали.</p>
                </div>
            </div>
        </div>
        <div class="reason-1 reason">
            <div class="reason-1-icon reason-icon">
        <iconpobeditel loading="lazy" width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg"/>
            </div>
            <div class="reason-1-text reason-text">
                <div class="reason-1-title reason-title">
                    <h3>Думайте верно и правильно</h3>
                </div>
                <div class="reason-1-information reason-information information">
                    <p>Это инструмент для концентраций подсознания, с которой можно изменить свои убеждения в лучшую сторону.</p>
                </div>
            </div>
        </div>
        <div class="reason-1 reason">
            <div class="reason-1-icon reason-icon">
                 <iconpobeditel loading="lazy" width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg"/>
            </div>
            <div class="reason-1-text reason-text">
                <div class="reason-1-title reason-title">
                    <h3>Будете тем кем вы хотели быть</h3>
                </div>
                <div class="reason-1-information reason-information information">
                    <p>Для нас это обычное дело, но люди называют это чудом.</p>
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
    .whyme{
        margin-bottom: 100px;
    }
    .whyme-content{
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
    }
    .whyme-title{
        text-align: center;
        margin: 0 auto 75px;
    }
    .whyme-title h2{
        font-size: 45px;
    }
    .hr-center hr{
        width: 100px;
        height: 4px;
        border-radius: 100px;
        background-color:#41cb52;
        box-shadow: 0px 0px 30px 0px rgb(0 0 0 / 10%);
        border-style: none;
    }
    .hr-center{
        margin: 20px 0 20px 0;
        text-align: center;
        display: inline-block;
    }
    .reason{
        width: 495px;
        min-height: 88px;
        border-radius: 4px 4px 4px 4px;
        box-shadow: 0px 0px 30px 0px rgb(0 0 0 / 10%);
        background-color: #FFFFFF;
        padding: 30px 30px 30px 30px;
        box-sizing: content-box;
        margin: 0 10px 20px 10px;
    }
    .reason-icon{
        flex-shrink: 0;
        padding-right: 25px;
    }
    .reason-icon svg{
        width: 56px;
        margin-top: 8px;
        float: left
    }
    .reason-icon svg path{
        fill:#41cb52;
    }
    .reason-title h3{
        color: #212121;
        font-size: 23px;
        font-weight: 700;
        margin: 0 0 10px 0;
    }
    .reason-information{
        color: #616161;
        font-weight: 400;
        font-style: normal;
        font-size: 16px;
        line-height: 1.5;
    }
    @media (max-width: 440px){}
</style>