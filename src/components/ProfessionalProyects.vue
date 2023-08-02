<template>
    <div class="container">
        <div class="content">
            <div class="head-container">
                <div class="container-text">
                        <h1>
                            My professional projects
                        </h1>
                </div>
                <div class="container-image">
                    <img src="../assets/img/logo_rose.png" alt="logo" class="image">
                </div>
            </div>
            <div class="main-container">
                <div class="carrusel-contenido">
                    <div class="carrusel-caja">
                        <div class="carrusel-elemento">
                            <img class="imagenes" src="https://via.placeholder.com/600/92c952" >
                        </div>
                        <div class="carrusel-elemento">   
                            <img class="imagenes" src="https://via.placeholder.com/600/f9cee5">
                        </div>
                        <div class="carrusel-elemento">   
                            <img class="imagenes" src="https://via.placeholder.com/600/372c93">                        
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'ProfessionalProyects',
}
</script>

<style scoped>
.main-container {
    display: flex;
    flex-direction: row;
}
.main-container > div {
    width: 50%;
}
.container {
  background-color: #141414;
  height: 100%;
}
.content {
    margin-right: 80px;
    border: solid 8px #EEBEAE;
    padding-bottom: 100px;
}
.head-container {
    display: flex;
    flex-direction: row;
}
.container-image {
    padding-left: 600px;
    text-align: right;
}
.container-text {
    font-family: 'Aileron', sans-serif;
    padding-left: 60px;
}
.container-text h1 {
    padding-top: 50px;
    font-size: 70px;
    text-shadow: 8px 0px #4B413D;
    color: #EEBEAE;
    width: fit-content;
}
.carrusel-caja {
    -moz-animation: automatizacion 10s infinite linear;
    -o-animation: automatizacion 10s infinite linear;
    -webkit-animation: automatizacion 10s infinite linear;
    animation: automatizacion 10s infinite linear;
    -webkit-transition: all 0.75s ease;
    -moz-transition: all 0.75s ease;
    -ms-transition: all 0.75s ease;
    -o-transition: all 0.75s ease;
    transition: all 0.75s ease;
    height: 500px;
    width: 300%;
}
.carrusel-contenido {
    margin: 0 auto;
    overflow: hidden;
    text-align: left;
}
.imagenes{
    height: 500px;
    width: 100%;
}
.carrusel-elemento {
    float: left;
    width: 33.333%;
}
@-moz-keyframes automatizacion {
    0% {
        margin-left: 0;
    }
    30% {
        margin-left: 0;
    }
    35% {
        margin-left: -100%;
    }
    65% {
        margin-left: -100%;
    }
    70% {
        margin-left: -200%;
    }
    95% {
        margin-left: -200%;
    }
    100% {
        margin-left: 0;
    }
}
@-webkit-keyframes automatizacion {
    0% {
        margin-left: 0;
    }
    30% {
        margin-left: 0;
    }
    35% {
        margin-left: -100%;
    }
    65% {
        margin-left: -100%;
    }
    70% {
        margin-left: -200%;
    }
    95% {
        margin-left: -200%;
    }
    100% {
        margin-left: 0;
    }
}
@keyframes automatizacion {
    0% {
        margin-left: 0;
    }
    30% {
        margin-left: 0;
    }
    35% {
        margin-left: -100%;
    }
    65% {
        margin-left: -100%;
    }
    70% {
        margin-left: -200%;
    }
    95% {
        margin-left: -200%;
    }
    100% {
        margin-left: 0;
    }
}
</style>