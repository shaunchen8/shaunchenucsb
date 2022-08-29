<template>
  <div style="padding-top:3em;">
    &nbsp;
  </div>
  <div class="title">cinematics</div>

  <div class="container">
    <div class="container-box card-cine">
      <div class="section"><iframe src="https://www.youtube.com/embed/x4MalPxgG5U" class="vid"></iframe></div>
      <div class="section">
        <strong>san diego trip</strong>
        <p>It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using</p>
      </div>
    </div>
  </div>
  
  <div class="container">
    <div class="container-box-2 card-cine">
      <div class="section"><iframe src="https://www.youtube.com/embed/3q2eF8Lmhws" class="vid"></iframe></div>
      <div class="section">
        <strong>water bottle rocket launch</strong>
        <p>Recorded with Phantom v711 Digital High Speed Camera at 3000 frames per second</p>
      </div>
    </div>
  </div>

  <div class="container">
    <div class="container-box card-cine">
      <div class="section"><iframe src="https://www.youtube.com/embed/f0IH_duFJzU" class="vid"></iframe></div>
      <div class="section">
        <strong>csgo highlight</strong>
        <p>back when i was good at this game</p>
      </div>
    </div>
  </div>
  
</template>


<style>

  .title{
      padding-top:5em;
      padding-bottom: 1em;
      font-family: Poppins;
      font-weight: bold;
      font-size: 24px;
  }

  .vid{
    height: 300px;
    width: 480px;
  }

  .container-box{
    background-color: aliceblue;
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 2em 5em;
  }

  .container-box-2{
    background-color: aliceblue;
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 2em 5em;
    flex-direction: row-reverse;
  }

  .section{
    flex:1;
    padding: 0em 3em;
    /* border: 4px solid red; */
  }

  
  .card-cine {
    background: aliceblue;
    box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
    border-radius: 5px;
    width: 1000px;
    height: 300px;
    margin: 1em 2em;
    display: flex;
    justify-content: center;
    align-items: center;
  }

</style>

