<template>
    <div class="background-home">
        <div class="container">
            <span class="spacer-line"></span>
            <div class="container-image">
                <img class="image" src="../assets/img/logo_rose.png" alt="logo">
            </div>
            <div class="container-title">
                <h1>
                    Rosanyela <br>
                    Contreras
                </h1>
            </div>
            <div class="container-sub-title">
                <h1>
                    Community Manager - Copywriter - Digital Designer.
                </h1>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'HomeComponent'
}
</script>

<style>
.background-home {
    background-image: url('./../assets/img/fondo_principal.jpg');
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    width: 100%;
    height: 95vh;
}
.spacer-line {
    position: absolute;
    top: 10;
    left: 80px;
    width: 8px;
    height: 70%;
    margin-top: 20px;
    background-color: #EEBEAE;

}
.container {
    padding: 60px 0px 60px 80px;
}
.container-image {
    text-align: left;
    height: 100%;
}
.container-title {
    height: 100%;
    text-align: left;
    font-family: 'Caveat', cursive;
    color: #EEBEAE;
    font-size: 60px;
    text-shadow: 14px 0px #4B413D;
    margin-left: 60px;
}
.image {
    width: 250px;
    height: 250px;
}
.container-sub-title {
    font-family: 'Aileron', sans-serif;
    color: white;
    margin-left: 60px;
    margin-top: -50px;
}
</style>