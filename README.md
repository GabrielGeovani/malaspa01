<ion-header class="header1" style="background-color: green">

  <ion-navbar >
    <ion-title class="title">Introdução</ion-title>
  </ion-navbar>

</ion-header>


<ion-content  padding style="background-color:darkgreen">

  <ion-slides pager >

    <ion-slide style="background-color: green">
      <img class="Gif" src="assets/imgs/verde.gif">
      <h2 class="text1">Bem Vindo ao aplicativo</h2>
      <br>
      <h1 class="NUTRINOS">NUTRINOS</h1>

    </ion-slide>
  
    <ion-slide style="background-color: green">
        <img src="assets/imgs/back01.png">
        <h2 class="slide2_text">Sua saúde e bem estar é a nossa  prioridade!</h2>
    </ion-slide>
  
    <ion-slide style="background-color: green">
        <img class="img3" src="assets/imgs/maca.png">
      <h2 class="text3">O aplicativo perfeito para manter uma rotina saúdavel na praticidade do seu celuluar!!</h2>
      <ion-buttons >
        <button ion-button style="background-color:darkgreen" (click)="GoToTabs()">CONTINUAR </button>
      </ion-buttons>
    </ion-slide>
  
  </ion-slides>


</ion-content>
