<template>
    <div class="main">
 <div class="main-content content">
   <div class="main-text-content">
     <div class="main-text-wrapper">
       <h1><span>Гипнотерапия и Целительство
</span><br> На Проффесиональном
Уровне</h1>
         <p>Вы многие годы не понимая ситуацию безуспешно пытаетесь сохранить или создать семью, прилично зарабатывать и быть здоровым(ой). Но это не дало вам ничего кроме разочарования?<span> На БЕСПЛАТНОЙ консультации Я Вам раскрою настоящую причину, которая забрала у вас годы радости и наслаждений.</span><br>
</p>
       <div class="buttons">
         <div class="main-button-zapis main-button">
           <a>Записаться</a>
         </div>
         <div class="main-button-konsult main-button">
           <a>Консультация</a>
         </div>
       </div>
     </div>
   </div>
 </div>
 <v-app>
      <v-dialog v-model="dialog" width="600">
        <v-card height="800">
          <div class="window">
            <div class="window-content">
               <div class="window-title">
                       <p>Оставьте заявку для<br>
                           <span>Обратной связи</span></p>
                   </div>
                   <div class="window-forms">
                <keep-alive>
                <zapisatsa @someEvent="Close"/>

                </keep-alive>
              </div>
            </div>
          </div>
        </v-card>
      </v-dialog>
    </v-app>
</div>
</template>
<script>
    export default {
  data () {
    return {
        dialog: false,
        data:''
    }
  },
        methods:{
    Close () {
      this.dialog = false
    },}
}

</script>
<style>
.main{
    background: url(/background.jpeg);
    height: 875px;
}
    .main-content{
        position: relative;
        z-index: 3;
        height: 100%;
        display: flex;
        align-items: center;
    }
    .main:after {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: rgba(0,0,0,0.7);
      height: inherit;
}
    .main-text-content{
      padding: 0 15px;
      position: relative;
      
    }
    .main-text-wrapper h1{
        font-size: 55px;
        font-weight: 800;
        color: #FFFFFF;
        line-height: 1.2;
    }
    .main-text-wrapper h1 span{
        color: #41cb52;
    }
    .main-text-wrapper p{
        font-size: 18px;
        color: #FFFFFF;
        margin: 25px 0 35px;
        width: 65%;
    }
    .main-text-wrapper p span{
        display: inline-block;
        padding-left: 10px;
        margin-top: 16px
    }
    .main-button{
        width: 200px;
        height: 50px;
        display: flex;
        justify-content: center;
        align-items: center;
        border-radius: 10px;
        font-weight: 600;
        font-size: 17px;
        line-height: 0;
        margin: 12px;
    }
    .main-button-zapis{
        background-color: #41cb52;
    }
    .main-button-konsult{
        border: 1px solid #FFFFFF;
    }
    .buttons{
        display: flex;
        flex-wrap: wrap;
    }
    @media (max-width: 991px){
        .main-text-wrapper h1{
            font-size: 40px;
        }
    }
    @media (max-width: 686px){
        .main-text-wrapper h1{
            font-size: 30px;
        }
        .main-text-wrapper p{
             width: auto;
        }
        .buttons{
            justify-content: center;
    }
    }
    @media (max-width: 565px){
        .main-text-wrapper h1{
            font-size: 7vw;
        }
        .main-text-wrapper p{
             font-size: 17px;
        }
    }
</style>