<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>SONYFREE</title>
</head>
<style>
*, html , body{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
  .ke{
    background-position: center;
    background-size: cover;
    background-attachment: fixed;
    background-color: red;
    width: 100%;
    height: 100vh;
  }
  .a{
    background-image: url('a.jpg');
  }
  .b{
    background-image: url('b.jpg');
    color: aqua;
    align-items: center;
    justify-content: center;
    height: 100vh;
    font-family: monaco;
  }
  .c{
    background-image: url('c.jpg');
  }
  .cta{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100px;
  }
  .text{
    box-shadow: white;
    text-shadow: white;
    font-size: 2em;
    color: lightgray;
    font-family: monaco;
    animation: blinker 1s linear infinite; 
} 
  @keyframes blinker { 
  50% { 
    opacity: 0; 
  } 
    
  }
  .wa{
     display: flex;
     justify-content: center;
     align-items: center;
     height: 100vh;
     font-size: 20px;
     font-family: fantasy;
     color: white;
  }
  .puisi{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }
  .judul{
    align-items: center;
    justify-content: center;
    display: flex;
    font-size: 20px;
    margin: block;
  }
  
 
</style>
<body>
  <div class="ke a">
      <div class="cta">
    <div class="text">HELLO IM SONY
     </div>
    </div>
  </div>
  <div class="ke b">
    <div class="judul">IBU</div>
    <div class="puisi">
Ada banyak panggilanmu bunda, mama, atau ibu Satu yang pasti, panggilan itu lebih mulia daripada ratu Kau relakan tubuhmu, sebagai pintu masuk kami ke dunia ini Kau hancurkan egomu, demi hadirkan tawa Dibalik derai tangis kami, kau adalah pelangi dalam jiwaku Kau lah kehangatan, disaat aku lelap dalam pangkuanmu
</div>
  </div>
  
  <div class="ke c">
          <div class="wa">
        <span><marquee>
      <a href="https://wa.me/6283847561307?text=contoh%20isi%20pesan%20dikirim%20via%20whatsapp"><img src="call.jpg" style="height:50px;width:auto;">
        </a>
        </span></marquee>
      </div>
  </div>
  
</body>
</html>
