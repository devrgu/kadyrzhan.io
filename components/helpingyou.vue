<template>
    <div class="whatdoing">
        <div class="whatdoing-content content">
            <div class="whatdoing-img">
                <img src="/photo-section-1.jpeg">
            </div>
            <div class="whatdoing-text">
                <div class="whatdoing-title title">
                    <h2>Вы не потеряли надежду?<br> <span>Значит выход есть!</span></h2>
                    <div class="hr-center">
                    <hr>
                    </div>
                </div>
                <div class="whatdoing-information information">
                    <p>
                    <span>
Меня зовут Lorem ipsum, я сертифицированный специалист и эксперт American Academy Holistic Mind Therapy.</span>
<span>Обращайтесь ко мне, я знаю всю вашу боль. Я знаю, как пройти через это. Вам в подсознание нужен образ мира, которого вы не замечаете. Это ваше притяжение! Я приведу вас в ресурсное состояние покоя. Только при этом раскладе у вас откроется притяжение богатства и денег.</span>
<span>Я не очередной семейный психолог, к которому нужно ходить как на работу. Вам не понадобится много сеансов, ведь я не просто выслушиваю своих пациентов, а помогаю устранить первопричину проблем в бизнесе и даю четкие инструкции, как снова привести бизнес в порядок и забыть проблемы которые когда-то не оставляли вас в покое.</span></p>
                </div>
                <div class="avtor">
                       <div class="avtor-img"></div>
                       <div class="avtor-text">
                           <h3>Lorem ipsum dolor sit</h3>
                           <p>Sit amet, onsectetur adipiscing elit</p>
                       </div>
                   </div>
            </div>
        </div>
    </div>
</template>
<style>
    .whatdoing{
        padding: 10px 0 140px 0    
    }
    .whatdoing-content{
        display: flex;
    }
    .title p{
        font-size: 18px;
        color: #A7A7A7
    }
    .title h2{
        color: #232323;
        font-size: 39px;
        font-weight: 800;
        line-height: 1.2;
    }
    .title h2 span{
        color: #41cb52;
    }
    .whatdoing-img{
        width: 100%;
        overflow: hidden;
        padding: 0 0 58% 0;
        position: relative;
    }
    .whatdoing-img img{
        width: 100%;
        height: 565px;
        object-fit: cover;
        position: absolute;
        top: 0;
        left: 0;
    }

    .whatdoing-text{
        margin-left: 25px;
        min-width: 553px;
        flex-shrink: 6;
    }
    .whatdoing-title{
        display: inline-block;
    }
    .information{
        color: #343a40;
        font-size: 18px;
        margin: 
    }
    .information p span{
        margin: 6px 0;
        display: inline-block;
    }
    
    .avtor{
        display: flex;
        margin: 32px 0 0 24px;
    }
    .avtor-img{
        width: 90px;
        height: 90px;
        background-color: #A7A7A7;
        background-size: cover;
        border-radius: 100px;
    }
    .avtor-text{
        margin-left: 16px;
        margin-top: 16px;
    }
    .avtor-text h3{
        font-size: 18px;
        color: #232323;
        font-weight: 700;
    }
    .avtor-text p{
        font-size: 16px;
        color: #A7A7A7;
        font-weight: 400;
    }
    @media (max-width: 991px){
        .whatdoing-content{
        flex-wrap: wrap
        }
        .whatdoing-text{
            margin-top: 48px;
            min-width: 0;
        }
    }
    @media (max-width: 656px){
        .title h2{
            font-size: 30px !important;
        }
    }
    @media (max-width: 465px){
        .title h2{
            font-size: 24px !important;
        }
        .whatdoing-text{
            margin-left: 16px;
            margin-right: 16px
        }
        .avtor-img{
            width: 10vw;
        }
    }
</style>