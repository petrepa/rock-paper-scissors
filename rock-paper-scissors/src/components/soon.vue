<script setup lang="ts">


</script>

<template>
  <div>
    <div class="background">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
    </div>
    <div class="container">
        <h1>🪨 📃 ✂️</h1>
        <h2 style="text-align:center; color:#FAFAFA;">COMING SOMETIME<br>idk rly hehe</h2>
        <img style="width:90vw; max-height: 70vh;" class="construction-img" src="../assets/construction.svg"
            alt="Under construction" />
    </div>
  </div>
</template>

<style scoped>
body {
    font-family: "Merriweather Sans";
}

.container {
    height: 100%;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;


}

@keyframes move {
    100% {
        transform: translate3d(0, 0, 1px) rotate(360deg);
    }
}

.background {
    position: fixed;
    width: 100vw;
    height: 100vh;
    top: 0;
    left: 0;
    background: #3E1E68;
    overflow: hidden;
    z-index: -1;
}

.background span {
    width: 2vmin;
    height: 2vmin;
    border-radius: 2vmin;
    backface-visibility: hidden;
    position: absolute;
    animation: move;
    animation-duration: 7;
    animation-timing-function: linear;
    animation-iteration-count: infinite;
}


.background span:nth-child(0) {
    color: #583C87;
    top: 69%;
    left: 70%;
    animation-duration: 384s;
    animation-delay: -79s;
    transform-origin: 12vw -19vh;
    box-shadow: -4vmin 0 1.4382411640396922vmin currentColor;
}

.background span:nth-child(1) {
    color: #FFACAC;
    top: 45%;
    left: 48%;
    animation-duration: 18s;
    animation-delay: -302s;
    transform-origin: -23vw 4vh;
    box-shadow: -4vmin 0 1.1054406166375406vmin currentColor;
}

.background span:nth-child(2) {
    color: #FFACAC;
    top: 80%;
    left: 60%;
    animation-duration: 314s;
    animation-delay: -5s;
    transform-origin: 17vw 20vh;
    box-shadow: -4vmin 0 0.5496914660406691vmin currentColor;
}

.background span:nth-child(3) {
    color: #FFACAC;
    top: 41%;
    left: 100%;
    animation-duration: 434s;
    animation-delay: -420s;
    transform-origin: 25vw -10vh;
    box-shadow: 4vmin 0 0.8359693155254893vmin currentColor;
}

.background span:nth-child(4) {
    color: #E45A84;
    top: 86%;
    left: 2%;
    animation-duration: 369s;
    animation-delay: -367s;
    transform-origin: 10vw 4vh;
    box-shadow: -4vmin 0 1.2884069570981014vmin currentColor;
}

.background span:nth-child(5) {
    color: #FFACAC;
    top: 88%;
    left: 47%;
    animation-duration: 318s;
    animation-delay: -67s;
    transform-origin: 14vw -9vh;
    box-shadow: 4vmin 0 1.4438471064138008vmin currentColor;
}

.background span:nth-child(6) {
    color: #E45A84;
    top: 91%;
    left: 50%;
    animation-duration: 116s;
    animation-delay: -293s;
    transform-origin: -5vw -9vh;
    box-shadow: 4vmin 0 1.1268726039204893vmin currentColor;
}

.background span:nth-child(7) {
    color: #FFACAC;
    top: 63%;
    left: 45%;
    animation-duration: 385s;
    animation-delay: -137s;
    transform-origin: -6vw 16vh;
    box-shadow: 4vmin 0 1.3916574074896724vmin currentColor;
}

.background span:nth-child(8) {
    color: #FFACAC;
    top: 81%;
    left: 83%;
    animation-duration: 277s;
    animation-delay: -104s;
    transform-origin: 15vw 21vh;
    box-shadow: 4vmin 0 0.8536631433265818vmin currentColor;
}

.background span:nth-child(9) {
    color: #E45A84;
    top: 6%;
    left: 93%;
    animation-duration: 338s;
    animation-delay: -393s;
    transform-origin: 24vw -9vh;
    box-shadow: -4vmin 0 0.7360481744360312vmin currentColor;
}

.background span:nth-child(10) {
    color: #FFACAC;
    top: 80%;
    left: 82%;
    animation-duration: 154s;
    animation-delay: -76s;
    transform-origin: 22vw 0vh;
    box-shadow: -4vmin 0 0.970780004436999vmin currentColor;
}

.background span:nth-child(11) {
    color: #583C87;
    top: 31%;
    left: 58%;
    animation-duration: 232s;
    animation-delay: -288s;
    transform-origin: -3vw 17vh;
    box-shadow: 4vmin 0 0.6581662391582317vmin currentColor;
}

.background span:nth-child(12) {
    color: #583C87;
    top: 60%;
    left: 21%;
    animation-duration: 334s;
    animation-delay: -207s;
    transform-origin: -7vw -16vh;
    box-shadow: 4vmin 0 0.5442555481941835vmin currentColor;
}

.background span:nth-child(13) {
    color: #583C87;
    top: 65%;
    left: 28%;
    animation-duration: 70s;
    animation-delay: -123s;
    transform-origin: 12vw 9vh;
    box-shadow: 4vmin 0 0.8739194021727354vmin currentColor;
}

.background span:nth-child(14) {
    color: #E45A84;
    top: 75%;
    left: 66%;
    animation-duration: 431s;
    animation-delay: -293s;
    transform-origin: -3vw 18vh;
    box-shadow: 4vmin 0 1.2158256845118114vmin currentColor;
}

.background span:nth-child(15) {
    color: #E45A84;
    top: 59%;
    left: 56%;
    animation-duration: 316s;
    animation-delay: -125s;
    transform-origin: -14vw -22vh;
    box-shadow: 4vmin 0 1.0127534532607965vmin currentColor;
}

.background span:nth-child(16) {
    color: #583C87;
    top: 4%;
    left: 20%;
    animation-duration: 277s;
    animation-delay: -40s;
    transform-origin: 19vw -18vh;
    box-shadow: 4vmin 0 1.2152045119953467vmin currentColor;
}

.background span:nth-child(17) {
    color: #E45A84;
    top: 50%;
    left: 88%;
    animation-duration: 294s;
    animation-delay: -245s;
    transform-origin: 16vw 6vh;
    box-shadow: 4vmin 0 1.0348344879902749vmin currentColor;
}

.background span:nth-child(18) {
    color: #E45A84;
    top: 76%;
    left: 38%;
    animation-duration: 125s;
    animation-delay: -15s;
    transform-origin: 13vw 6vh;
    box-shadow: -4vmin 0 0.5015545335768412vmin currentColor;
}

.background span:nth-child(19) {
    color: #583C87;
    top: 37%;
    left: 36%;
    animation-duration: 332s;
    animation-delay: -306s;
    transform-origin: 3vw -11vh;
    box-shadow: -4vmin 0 1.0562441650239192vmin currentColor;
}

.background span:nth-child(20) {
    color: #E45A84;
    top: 34%;
    left: 97%;
    animation-duration: 77s;
    animation-delay: -135s;
    transform-origin: 15vw 24vh;
    box-shadow: 4vmin 0 0.5390153188335811vmin currentColor;
}

.background span:nth-child(21) {
    color: #E45A84;
    top: 93%;
    left: 51%;
    animation-duration: 95s;
    animation-delay: -77s;
    transform-origin: 3vw -17vh;
    box-shadow: -4vmin 0 1.1156425726222516vmin currentColor;
}

.background span:nth-child(22) {
    color: #E45A84;
    top: 70%;
    left: 24%;
    animation-duration: 59s;
    animation-delay: -240s;
    transform-origin: 22vw 14vh;
    box-shadow: 4vmin 0 1.425351353151411vmin currentColor;
}

.background span:nth-child(23) {
    color: #FFACAC;
    top: 15%;
    left: 15%;
    animation-duration: 321s;
    animation-delay: -424s;
    transform-origin: 9vw 16vh;
    box-shadow: 4vmin 0 0.9491882364440432vmin currentColor;
}

.background span:nth-child(24) {
    color: #FFACAC;
    top: 27%;
    left: 26%;
    animation-duration: 340s;
    animation-delay: -418s;
    transform-origin: 9vw 2vh;
    box-shadow: -4vmin 0 1.1256600031051487vmin currentColor;
}

.background span:nth-child(25) {
    color: #FFACAC;
    top: 63%;
    left: 72%;
    animation-duration: 90s;
    animation-delay: -32s;
    transform-origin: 3vw -11vh;
    box-shadow: 4vmin 0 1.2101817709601972vmin currentColor;
}

.background span:nth-child(26) {
    color: #E45A84;
    top: 65%;
    left: 87%;
    animation-duration: 288s;
    animation-delay: -83s;
    transform-origin: -2vw 15vh;
    box-shadow: 4vmin 0 1.162384161875211vmin currentColor;
}

.background span:nth-child(27) {
    color: #FFACAC;
    top: 18%;
    left: 62%;
    animation-duration: 199s;
    animation-delay: -47s;
    transform-origin: 20vw 16vh;
    box-shadow: -4vmin 0 1.0872009672646974vmin currentColor;
}

.background span:nth-child(28) {
    color: #FFACAC;
    top: 58%;
    left: 18%;
    animation-duration: 302s;
    animation-delay: -2s;
    transform-origin: -17vw -6vh;
    box-shadow: 4vmin 0 0.5704864756942163vmin currentColor;
}

.background span:nth-child(29) {
    color: #583C87;
    top: 42%;
    left: 4%;
    animation-duration: 48s;
    animation-delay: -238s;
    transform-origin: -10vw 2vh;
    box-shadow: 4vmin 0 1.4335476369855558vmin currentColor;
}

.background span:nth-child(30) {
    color: #FFACAC;
    top: 10%;
    left: 57%;
    animation-duration: 110s;
    animation-delay: -281s;
    transform-origin: -16vw -8vh;
    box-shadow: 4vmin 0 0.5955939767787923vmin currentColor;
}

.background span:nth-child(31) {
    color: #E45A84;
    top: 57%;
    left: 16%;
    animation-duration: 417s;
    animation-delay: -425s;
    transform-origin: 24vw 6vh;
    box-shadow: 4vmin 0 0.9466537338525076vmin currentColor;
}

.background span:nth-child(32) {
    color: #E45A84;
    top: 35%;
    left: 89%;
    animation-duration: 251s;
    animation-delay: -156s;
    transform-origin: 12vw 18vh;
    box-shadow: 4vmin 0 1.2244702370039708vmin currentColor;
}

.background span:nth-child(33) {
    color: #FFACAC;
    top: 2%;
    left: 43%;
    animation-duration: 123s;
    animation-delay: -371s;
    transform-origin: 15vw -13vh;
    box-shadow: 4vmin 0 1.2268318281563888vmin currentColor;
}

.background span:nth-child(34) {
    color: #E45A84;
    top: 64%;
    left: 10%;
    animation-duration: 176s;
    animation-delay: -402s;
    transform-origin: 15vw -12vh;
    box-shadow: 4vmin 0 1.1823426910472865vmin currentColor;
}
</style>
