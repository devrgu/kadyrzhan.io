<template>
<div class="konsultatsia">
    <div class="konsultatsia-content">
       <div class="konsultatsia-wrap content">
        <div class="konsultatsia-title title">
            <h3>Обратитесь ко мне!</h3>   
            <h2>Возникли вопросы? Получите<br>бесплатную консультацию!</h2>
        </div>
        <div class="main-button-continue-2 main-button">
           <a>КОНСУЛЬТАЦИЯ</a>
        </div>
    </div>
    </div>
    <div class="konsultatsia-recvisits">
        <div class="office recvisit">
            <div class="recvisit-box-icon">
                <iconpobeditel  width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg"/>
            </div>
            <div class="recvisit-box-text">
                <div class="recvisit-box-title">
                    <h3>Адрес офиса</h3>
                </div>
                <div class="recvisit-box-information information">
                    <p>Aksai 3a, Almaty 3335Z</p>
                </div>
            </div>
        </div>
        <div class="office recvisit">
            <div class="recvisit-box-icon">
                <iconpobeditel  width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg"/>
            </div>
            <div class="recvisit-box-text">
                <div class="recvisit-box-title">
                    <h3>Электронная почта</h3>
                </div>
                <div class="recvisit-box-information information">
                    <p>example@gmail.com</p>
                </div>
            </div>
        </div>
        <div class="office recvisit">
            <div class="recvisit-box-icon">
                <iconpobeditel  width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg"/>
            </div>
            <div class="recvisit-box-text">
                <div class="recvisit-box-title">
                    <h3>Номер телефона</h3>
                </div>
                <div class="recvisit-box-information information">
                    <p>+8 (776) 343 30 15</p>
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
    .konsultatsia{
        min-height: 500px;
        background-color: #FFFFFF;
        margin-bottom: 70px;
    }
    .konsultatsia-content{
        background-color: #19D567;
    }
    .konsultatsia-wrap{
        text-align: center;
        padding-top: 90px;
        position: relative;
        height: 500px;
        
    }
    div.konsultatsia-title h2{
        color: #FFFFFF;
        font-size: 45px;
        margin: 10px 0 35px 0;
    }
    div.konsultatsia-title h3{
        color: #FFFFFF;
        font-size: 24px;
        font-weight: 500;
    }
    div .main-button-continue-2{
        background-color: #FFFFFF;
        color: #41cb52;
        display: inline-flex;
        border-radius: 5px;
        height: 55px;
    }
    .konsultatsia-recvisits{
        display: flex;
        position: relative;
        bottom: 70px;
        justify-content: center;
        flex-wrap: wrap;
    }
    .recvisit{
        width: 353px;
        height: 90px;
        box-sizing: content-box;
        background: #ffffff;
        box-shadow: 0 0 5px rgb(0 0 0 / 25%);
        border-bottom: 3px solid #41cb52;
        border-radius: 6px 6px 6px 6px;
        padding: 30px 20px 25px 20px;
        position: relative;
        display: flex;
        margin: 0 10px 24px 10px;
    }
    .recvisit-box-text{
        text-align: initial !important;
        margin-top: 5px;
    }
    .recvisit-box-icon{
        flex-shrink: 0;
        width: 90px;
        height: 90px;
        border-radius: 90px;
        background-color: #f7f9fa;
        display: flex;
        justify-content: center;
        align-items: center;
        margin-right: 20px;
    }
    .recvisit-box-icon svg{
        width: 50px;
    }
    .recvisit-box-icon svg path{
        fill: #41cb52 !important;
    }
    .recvisit-box-title h3{
        color: #232323;
        font-size: 18px;
        text-transform: uppercase;
        line-height: 1.3;
        margin: 10px 0;
    }
    .recvisit-box-information{
        font-size: 16px;
        color: #616161;
    }
    @media (max-width: 440px){
        .recvisit{
            width: 100%;
        }
        div.konsultatsia-title h3{
            font-size: 4.5vw;
        }
        div.konsultatsia-title h2{
            font-size: 6vw !important 
        }
    }
</style>