<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
<meta name="theme-color" content="#07080a">
<meta name="apple-mobile-web-app-capable" content="yes">
<title>HiKiTaV2.1</title>

<style>
*{
 box-sizing:border-box;
 -webkit-tap-highlight-color:transparent;
}

html,body{
 margin:0;
 min-height:100%;
 background:#07080a;
 color:#f4f4f5;
 font-family:-apple-system,BlinkMacSystemFont,"SF Pro Display","Helvetica Neue",Arial,sans-serif;
}

body{
 overflow-x:hidden;
 background:
 radial-gradient(circle at 50% -140px,#3d4047 0,#191b1f 28%,#07080a 72%);
}

/* =========================
   LOADING
========================= */

.loading{
 position:fixed;
 inset:0;
 z-index:99999;
 display:flex;
 flex-direction:column;
 align-items:center;
 justify-content:center;
 background:
 radial-gradient(circle at center,#1b1d21 0,#08090b 55%);
 animation:loadingOut .7s ease 2.7s forwards;
}

.loadingLogo{
 width:64px;
 height:64px;
 display:flex;
 align-items:center;
 justify-content:center;
 border:1px solid #555960;
 border-radius:20px;
 background:linear-gradient(145deg,#3c3f45,#101214);
 box-shadow:
  inset 0 1px rgba(255,255,255,.12),
  0 20px 55px rgba(0,0,0,.55);
 font-size:24px;
 font-weight:950;
 animation:pulse 1.6s ease-in-out infinite;
}

.loadingTitle{
 margin-top:19px;
 font-size:33px;
 font-weight:950;
 letter-spacing:2px;
}

.loadingSub{
 margin-top:8px;
 color:#777c84;
 font-size:9px;
 letter-spacing:3px;
 text-transform:uppercase;
}

.loader{
 width:190px;
 height:3px;
 margin-top:23px;
 overflow:hidden;
 border-radius:10px;
 background:#282b30;
}

.loader:after{
 content:"";
 display:block;
 width:0;
 height:100%;
 border-radius:10px;
 background:#eeeeef;
 animation:load 2.35s ease forwards;
}

@keyframes load{
 from{width:0}
 to{width:100%}
}

@keyframes pulse{
 0%,100%{transform:scale(1)}
 50%{transform:scale(1.04)}
}

@keyframes loadingOut{
 to{
  opacity:0;
  visibility:hidden;
  pointer-events:none;
 }
}

/* =========================
   APP
========================= */

.app{
 width:100%;
 max-width:570px;
 margin:auto;
 padding:18px 15px calc(38px + env(safe-area-inset-bottom));
}

/* =========================
   HEADER
========================= */

.top{
 display:flex;
 align-items:center;
 justify-content:space-between;
 margin-bottom:18px;
}

.brand{
 display:flex;
 align-items:center;
 gap:11px;
}

.logo{
 width:45px;
 height:45px;
 display:flex;
 align-items:center;
 justify-content:center;
 border:1px solid #41444a;
 border-radius:15px;
 background:linear-gradient(145deg,#373a40,#101214);
 box-shadow:
  inset 0 1px rgba(255,255,255,.1),
  0 12px 30px rgba(0,0,0,.45);
 font-size:17px;
 font-weight:950;
}

.brandName{
 font-size:19px;
 font-weight:900;
 letter-spacing:.6px;
}

.admin{
 margin-top:4px;
 color:#777c84;
 font-size:9px;
 letter-spacing:.9px;
}

.online{
 display:flex;
 align-items:center;
 gap:6px;
 padding:8px 11px;
 border:1px solid #292c31;
 border-radius:20px;
 background:rgba(17,19,21,.9);
 color:#b6b9be;
 font-size:9px;
 font-weight:800;
 letter-spacing:1px;
}

.dot{
 width:6px;
 height:6px;
 border-radius:50%;
 background:#e5e5e6;
 box-shadow:0 0 10px rgba(255,255,255,.8);
}

/* =========================
   HERO
========================= */

.hero{
 position:relative;
 overflow:hidden;
 padding:25px;
 border:1px solid #35383e;
 border-radius:26px;
 background:
 linear-gradient(135deg,rgba(55,58,64,.97),rgba(13,15,17,.99));
 box-shadow:
 0 25px 65px rgba(0,0,0,.45),
 inset 0 1px rgba(255,255,255,.07);
}

.hero:before{
 content:"";
 position:absolute;
 width:240px;
 height:240px;
 right:-105px;
 top:-145px;
 border-radius:50%;
 background:rgba(255,255,255,.07);
 filter:blur(17px);
}

.hero:after{
 content:"V2.1";
 position:absolute;
 right:18px;
 bottom:11px;
 color:rgba(255,255,255,.045);
 font-size:38px;
 font-weight:950;
}

.heroSmall{
 position:relative;
 color:#92979e;
 font-size:9px;
 font-weight:800;
 letter-spacing:2.1px;
 text-transform:uppercase;
}

.heroTitle{
 position:relative;
 margin-top:8px;
 font-size:30px;
 font-weight:950;
 letter-spacing:.7px;
}

.heroDesc{
 position:relative;
 margin-top:7px;
 color:#8b9097;
 font-size:11px;
}

.heroLine{
 position:relative;
 width:50px;
 height:3px;
 margin-top:17px;
 border-radius:10px;
 background:#ededee;
 box-shadow:0 0 12px rgba(255,255,255,.12);
}

/* =========================
   SECTION
========================= */

.section{
 margin-top:15px;
 overflow:hidden;
 border:1px solid #292c31;
 border-radius:22px;
 background:linear-gradient(180deg,#191b1f,#101214);
 box-shadow:0 17px 45px rgba(0,0,0,.32);
}

.sectionHead{
 padding:17px 18px 13px;
}

.sectionTitle{
 font-size:17px;
 font-weight:900;
 letter-spacing:.4px;
}

.sectionSub{
 margin-top:4px;
 color:#70757c;
 font-size:10px;
}

/* =========================
   FUNCTION ROW
========================= */

.item{
 min-height:61px;
 display:flex;
 align-items:center;
 justify-content:space-between;
 padding:0 17px;
 border-top:1px solid #292c31;
 transition:background .2s ease;
}

.item:has(.switch.on){
 background:rgba(255,255,255,.035);
}

.left{
 display:flex;
 align-items:center;
 gap:11px;
}

.functionIcon{
 width:30px;
 height:30px;
 display:flex;
 align-items:center;
 justify-content:center;
 border:1px solid #30343a;
 border-radius:9px;
 background:#111315;
 color:#9da2a8;
 font-size:9px;
 font-weight:900;
}

.functionName{
 font-size:14px;
 font-weight:750;
}

/* =========================
   SWITCH
========================= */

.switch{
 width:49px;
 height:29px;
 position:relative;
 flex:none;
 padding:0;
 border:1px solid #41454b;
 border-radius:30px;
 background:#292c31;
 cursor:pointer;
 transition:.22s ease;
}

.switch:after{
 content:"";
 position:absolute;
 top:2px;
 left:2px;
 width:23px;
 height:23px;
 border-radius:50%;
 background:#aeb2b8;
 box-shadow:0 2px 7px rgba(0,0,0,.7);
 transition:.22s ease;
}

.switch.on{
 background:#e3e4e5;
 border-color:#f2f2f3;
 box-shadow:0 0 15px rgba(255,255,255,.08);
}

.switch.on:after{
 left:22px;
 background:#101113;
}

/* =========================
   DEVICE
========================= */

.deviceGrid{
 display:grid;
 grid-template-columns:1fr 1fr;
 gap:9px;
 padding:0 14px 14px;
}

.device{
 min-height:73px;
 padding:13px;
 border:1px solid #292c31;
 border-radius:14px;
 background:#0c0e10;
}

.label{
 color:#656a71;
 font-size:8px;
 letter-spacing:1.2px;
 text-transform:uppercase;
}

.value{
 margin-top:7px;
 color:#e6e7e8;
 font-size:13px;
 font-weight:750;
 white-space:nowrap;
 overflow:hidden;
 text-overflow:ellipsis;
}

/* =========================
   GAME CARD
========================= */

.gameLauncher{
 position:relative;
 overflow:hidden;
 margin-top:15px;
 padding:16px;
 border:1px solid #383b40;
 border-radius:23px;
 background:
 linear-gradient(145deg,#22252a,#101214);
 box-shadow:
 0 20px 45px rgba(0,0,0,.36),
 inset 0 1px rgba(255,255,255,.05);
}

.gameLauncher:before{
 content:"";
 position:absolute;
 width:130px;
 height:130px;
 right:-65px;
 top:-70px;
 border-radius:50%;
 background:rgba(255,255,255,.045);
 filter:blur(12px);
}

.gameLauncherTitle{
 position:relative;
 display:flex;
 align-items:center;
 gap:11px;
 margin-bottom:14px;
}

.gameIcon{
 width:41px;
 height:41px;
 display:flex;
 align-items:center;
 justify-content:center;
 border:1px solid #42464c;
 border-radius:13px;
 background:#111315;
 color:#ededee;
 font-size:14px;
 font-weight:950;
}

.gameLauncherTitle strong{
 display:block;
 font-size:15px;
 font-weight:900;
}

.gameLauncherTitle small{
 display:block;
 margin-top:4px;
 color:#777c83;
 font-size:9px;
}

.launchButton{
 position:relative;
 width:100%;
 min-height:51px;
 display:flex;
 align-items:center;
 justify-content:space-between;
 padding:0 17px;
 border:1px solid #d6d7d9;
 border-radius:15px;
 background:linear-gradient(135deg,#f0f0f1,#bfc1c4);
 color:#0c0d0f;
 font-size:12px;
 font-weight:950;
 letter-spacing:1.3px;
 cursor:pointer;
 transition:.15s ease;
}

.launchButton b{
 font-size:25px;
 font-weight:400;
}

.launchButton:active{
 transform:scale(.97);
 filter:brightness(.88);
}

/* =========================
   GAME MENU
========================= */

.gameChoice{
 display:none;
 position:fixed;
 inset:0;
 z-index:9999;
 align-items:flex-end;
 justify-content:center;
 padding:15px 15px calc(15px + env(safe-area-inset-bottom));
 background:rgba(0,0,0,.72);
 backdrop-filter:blur(10px);
 -webkit-backdrop-filter:blur(10px);
}

.gameChoice.show{
 display:flex;
}

.gameChoiceBox{
 width:100%;
 max-width:530px;
 padding:16px;
 border:1px solid #3b3e44;
 border-radius:25px;
 background:linear-gradient(145deg,#202328,#101214);
 box-shadow:0 -12px 60px rgba(0,0,0,.58);
 animation:choiceUp .22s ease;
}

@keyframes choiceUp{
 from{
  opacity:0;
  transform:translateY(25px);
 }
 to{
  opacity:1;
  transform:translateY(0);
 }
}

.choiceHeader{
 display:flex;
 align-items:center;
 justify-content:space-between;
 padding:3px 3px 14px;
}

.choiceHeader strong{
 display:block;
 font-size:18px;
 font-weight:900;
}

.choiceHeader small{
 display:block;
 margin-top:4px;
 color:#777c83;
 font-size:10px;
}

.closeChoice{
 width:36px;
 height:36px;
 padding:0;
 border:1px solid #373a40;
 border-radius:50%;
 background:#111315;
 color:#c0c2c5;
 font-size:22px;
 line-height:1;
 cursor:pointer;
}

/* =========================
   GAME OPTIONS
========================= */

.gameOption{
 width:100%;
 min-height:68px;
 display:flex;
 align-items:center;
 margin-top:9px;
 padding:10px;
 border:1px solid #30343a;
 border-radius:17px;
 background:#111315;
 color:#fff;
 text-align:left;
 cursor:pointer;
 transition:.16s ease;
}

.gameOption:active{
 transform:scale(.98);
 background:#1b1e21;
}

.gameOptionIcon{
 width:44px;
 height:44px;
 display:flex;
 align-items:center;
 justify-content:center;
 flex:none;
 border:1px solid #41454b;
 border-radius:12px;
 background:linear-gradient(145deg,#34373c,#151719);
 color:#eee;
 font-size:10px;
 font-weight:950;
}

.gameOptionText{
 flex:1;
 min-width:0;
 margin-left:12px;
}

.gameOptionText strong{
 display:block;
 font-size:14px;
 font-weight:850;
}

.gameOptionText span{
 display:block;
 margin-top:4px;
 color:#777c83;
 font-size:9px;
}

.gameOption>b{
 padding:0 7px;
 color:#858990;
 font-size:23px;
 font-weight:400;
}

.choiceNote{
 padding-top:13px;
 color:#555a60;
 text-align:center;
 font-size:9px;
}

/* =========================
   FOOTER
========================= */

.footer{
 margin-top:19px;
 text-align:center;
 color:#4f5359;
 font-size:9px;
 letter-spacing:1.7px;
}

.version{
 margin-top:6px;
 color:#36393e;
 font-size:8px;
}

/* =========================
   SMALL DEVICES
========================= */

@media(max-width:360px){

 .app{
  padding-left:12px;
  padding-right:12px;
 }

 .heroTitle{
  font-size:26px;
 }

 .brandName{
  font-size:17px;
 }

 .admin{
  font-size:8px;
 }

 .deviceGrid{
  grid-template-columns:1fr;
 }

}
</style>
</head>

<body>

<!-- =========================
     LOADING
========================= -->

<div class="loading">

 <div class="loadingLogo">H</div>

 <div class="loadingTitle">
  HiKiTaV2.1
 </div>

 <div class="loadingSub">
  Initializing System
 </div>

 <div class="loader"></div>

</div>


<div class="app">

<!-- =========================
     HEADER
========================= -->

<div class="top">

 <div class="brand">

  <div class="logo">H</div>

  <div>

   <div class="brandName">
    HiKiTaV2.1
   </div>

   <div class="admin">
    ADMIN • HikiTa-Nguyễn Gia Nam
   </div>

  </div>

 </div>


 <div class="online">

  <span class="dot"></span>
  READY

 </div>

</div>


<!-- =========================
     HERO
========================= -->

<div class="hero">

 <div class="heroSmall">
  System Control Center
 </div>

 <div class="heroTitle">
  All Functions
 </div>

 <div class="heroDesc">
  Điều khiển và quản lý các tùy chọn
 </div>

 <div class="heroLine"></div>

</div>


<!-- =========================
     FUNCTIONS
========================= -->

<div class="section">

 <div class="sectionHead">

  <div class="sectionTitle">
   Functions
  </div>

  <div class="sectionSub">
   Chạm công tắc để bật hoặc tắt
  </div>

 </div>


 <div class="item">

  <div class="left">
   <div class="functionIcon">01</div>
   <div class="functionName">Bám đầu</div>
  </div>

  <button class="switch" type="button"></button>

 </div>


 <div class="item">

  <div class="left">
   <div class="functionIcon">02</div>
   <div class="functionName">Nhẹ Tâm</div>
  </div>

  <button class="switch" type="button"></button>

 </div>


 <div class="item">

  <div class="left">
   <div class="functionIcon">03</div>
   <div class="functionName">Fix Nặng Tâm</div>
  </div>

  <button class="switch" type="button"></button>

 </div>


 <div class="item">

  <div class="left">
   <div class="functionIcon">04</div>
   <div class="functionName">Fix Lố</div>
  </div>

  <button class="switch" type="button"></button>

 </div>


 <div class="item">

  <div class="left">
   <div class="functionIcon">05</div>
   <div class="functionName">Buff Nhạy</div>
  </div>

  <button class="switch" type="button"></button>

 </div>


 <div class="item">

  <div class="left">
   <div class="functionIcon">06</div>
   <div class="functionName">Buff 120HZ</div>
  </div>

  <button class="switch" type="button"></button>

 </div>


 <div class="item">

  <div class="left">
   <div class="functionIcon">07</div>
   <div class="functionName">Fix loạn Tâm</div>
  </div>

  <button class="switch" type="button"></button>

 </div>


 <div class="item">

  <div class="left">
   <div class="functionIcon">08</div>
   <div class="functionName">LockHead</div>
  </div>

  <button class="switch" type="button"></button>

 </div>

</div>


<!-- =========================
     DEVICE INFORMATION
========================= -->

<div class="section">

 <div class="sectionHead">

  <div class="sectionTitle">
   Device Information
  </div>

  <div class="sectionSub">
   Thông tin thiết bị hiện tại
  </div>

 </div>


 <div class="deviceGrid">


  <div class="device">

   <div class="label">
    Device
   </div>

   <div id="device" class="value">
    Checking...
   </div>

  </div>


  <div class="device">

   <div class="label">
    System
   </div>

   <div id="os" class="value">
    Checking...
   </div>

  </div>


  <div class="device">

   <div class="label">
    Battery
   </div>

   <div id="battery" class="value">
    Checking...
   </div>

  </div>


  <div class="device">

   <div class="label">
    Network
   </div>

   <div id="network" class="value">
    Checking...
   </div>

  </div>


  <div class="device">

   <div class="label">
    Display
   </div>

   <div id="display" class="value">
    Checking...
   </div>

  </div>


  <div class="device">

   <div class="label">
    Temperature
   </div>

   <div class="value">
    N/A
   </div>

  </div>


 </div>

</div>


<!-- =========================
     GAME LAUNCHER
========================= -->

<div class="gameLauncher">

 <div class="gameLauncherTitle">

  <div class="gameIcon">
   ▶
  </div>

  <div>

   <strong>
    Vào Game Ngay
   </strong>

   <small>
    Free Fire / Free Fire MAX
   </small>

  </div>

 </div>


 <button
  id="openGameMenu"
  class="launchButton"
  type="button">

  <span>
   VÀO GAME
  </span>

  <b>
   ›
  </b>

 </button>

</div>


<!-- =========================
     GAME CHOICE
========================= -->

<div
 id="gameChoice"
 class="gameChoice">


 <div class="gameChoiceBox">


  <div class="choiceHeader">

   <div>

    <strong>
     Chọn Game
    </strong>

    <small>
     Chọn phiên bản muốn mở
    </small>

   </div>


   <button
    id="closeGameMenu"
    class="closeChoice"
    type="button">

    ×

   </button>

  </div>


  <!-- FREE FIRE -->

  <button
   id="freeFire"
   class="gameOption"
   type="button">

   <div class="gameOptionIcon">
    FF
   </div>

   <div class="gameOptionText">

    <strong>
     Free Fire
    </strong>

    <span>
     Garena Free Fire
    </span>

   </div>

   <b>›</b>

  </button>


  <!-- FREE FIRE MAX -->

  <button
   id="freeFireMax"
   class="gameOption"
   type="button">

   <div class="gameOptionIcon">
    MAX
   </div>

   <div class="gameOptionText">

    <strong>
     Free Fire MAX
    </strong>

    <span>
     Garena Free Fire MAX
    </span>

   </div>

   <b>›</b>

  </button>


  <div class="choiceNote">
   Game cần được cài sẵn trên thiết bị.
  </div>


 </div>

</div>


<!-- FOOTER -->

<div class="footer">

 HiKiTaV2.1 • HikiTa-Nguyễn Gia Nam

 <div class="version">
  PREMIUM SYSTEM PANEL • V2.1
 </div>

</div>

</div>


<script>

/* =========================
   SWITCH
========================= */

document
.querySelectorAll(".switch")
.forEach(function(button){

 button.addEventListener(
  "click",
  function(){

   button.classList.toggle("on");

   playSound(
    button.classList.contains("on")
   );

  }
 );

});


/* =========================
   SOUND
========================= */

function playSound(on){

 try{

  var AudioContext=
   window.AudioContext||
   window.webkitAudioContext;

  if(!AudioContext)return;

  var ctx=new AudioContext();

  var osc=
   ctx.createOscillator();

  var gain=
   ctx.createGain();

  osc.type="sine";

  osc.frequency.value=
   on?650:430;

  gain.gain.setValueAtTime(
   .0001,
   ctx.currentTime
  );

  gain.gain.exponentialRampToValueAtTime(
   .035,
   ctx.currentTime+.02
  );

  gain.gain.exponentialRampToValueAtTime(
   .0001,
   ctx.currentTime+.12
  );

  osc.connect(gain);
  gain.connect(ctx.destination);

  osc.start();

  osc.stop(
   ctx.currentTime+.13
  );

 }catch(e){}

}


/* =========================
   DEVICE
========================= */

var ua=
 navigator.userAgent;

if(/iPhone/i.test(ua)){

 document
 .getElementById("device")
 .textContent="iPhone";

}
else if(/iPad/i.test(ua)){

 document
 .getElementById("device")
 .textContent="iPad";

}
else if(/Android/i.test(ua)){

 document
 .getElementById("device")
 .textContent="Android";

}
else{

 document
 .getElementById("device")
 .textContent="Mobile Browser";

}


/* =========================
   SYSTEM
========================= */

if(/iPhone|iPad|iPod/i.test(ua)){

 document
 .getElementById("os")
 .textContent="iOS";

}
else if(/Android/i.test(ua)){

 document
 .getElementById("os")
 .textContent="Android";

}
else{

 document
 .getElementById("os")
 .textContent="Unknown";

}


/* =========================
   DISPLAY
========================= */

document
.getElementById("display")
.textContent=
 screen.width+
 " × "+
 screen.height;


/* =========================
   NETWORK
========================= */

var connection=
 navigator.connection||
 navigator.mozConnection||
 navigator.webkitConnection;

if(
 connection &&
 connection.effectiveType
){

 document
 .getElementById("network")
 .textContent=
 connection
 .effectiveType
 .toUpperCase();

}
else if(navigator.onLine){

 document
 .getElementById("network")
 .textContent=
 "ONLINE";

}
else{

 document
 .getElementById("network")
 .textContent=
 "OFFLINE";

}


/* =========================
   BATTERY
========================= */

if(navigator.getBattery){

 navigator
 .getBattery()
 .then(function(battery){

  function updateBattery(){

   var text=
    Math.round(
     battery.level*100
    )+"%";

   if(battery.charging){

    text+=
     " • Charging";

   }

   document
   .getElementById("battery")
   .textContent=
    text;

  }

  updateBattery();

  battery.addEventListener(
   "levelchange",
   updateBattery
  );

  battery.addEventListener(
   "chargingchange",
   updateBattery
  );

 })
 .catch(function(){

  document
  .getElementById("battery")
  .textContent="N/A";

 });

}
else{

 document
 .getElementById("battery")
 .textContent="N/A";

}


/* =========================
   GAME MENU
========================= */

var gameChoice=
 document.getElementById(
  "gameChoice"
 );

var openGameMenu=
 document.getElementById(
  "openGameMenu"
 );

var closeGameMenu=
 document.getElementById(
  "closeGameMenu"
 );


/* OPEN */

openGameMenu.addEventListener(
 "click",
 function(){

  gameChoice
  .classList
  .add("show");

 }
);


/* CLOSE */

closeGameMenu.addEventListener(
 "click",
 function(){

  gameChoice
  .classList
  .remove("show");

 }
);


/* CLOSE BACKGROUND */

gameChoice.addEventListener(
 "click",
 function(event){

  if(
   event.target===
   gameChoice
  ){

   gameChoice
   .classList
   .remove("show");

  }

 }
);


/* =========================
   FREE FIRE
========================= */

document
.getElementById("freeFire")
.addEventListener(
 "click",
 function(){

  gameChoice
  .classList
  .remove("show");

  window.location.href=
   "freefire://";

 }
);


/* =========================
   FREE FIRE MAX
========================= */

document
.getElementById("freeFireMax")
.addEventListener(
 "click",
 function(){

  gameChoice
  .classList
  .remove("show");

  window.location.href=
   "freefiremax://";

 }
);

</script>

</body>
</html> 
