<template>
    <div class="container">
        <div class="content">
            <div class="container-image">
                <img src="../assets/img/logo_rose.png" alt="logo" class="image">
            </div>
            <div class="container-text">
                <h1>
                    "Creativity is intelligence having fun"
                </h1>
                <h2>
                    Albert Einstein
                </h2>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'PhraseComponent',
}
</script>

<style scoped>
.container {
  background-color: #141414;
  height: 100%;
}
.content {
    margin-right: 80px;
    border-bottom: solid 8px #EEBEAE;
    border-left: solid 8px #EEBEAE;
}
.container-image {
    width: 100%;
}
.container-text {
    width: 100%;
    margin-bottom: 100px;
}
.container-text h1 {
    font-family: 'Caveat', cursive;
    text-align: center;
    font-size: 130px;
    padding: 0px 200px 0px 200px;
    color: white;
    margin-top: -40px;
}
.container-text h2 {
    font-family: 'Aileron', sans-serif;
    text-align: center;
    font-size: 50px;
    color: #EEBEAE;
}
</style>