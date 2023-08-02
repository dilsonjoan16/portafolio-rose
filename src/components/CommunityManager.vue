<template>
    <div class="container">
        <div class="content">
            <div class="container-image">
                <img src="../assets/img/logo_rose.png" alt="logo" class="image">
            </div>
            <div class="container-content">
                <img src="../assets/img/community_manager.jpg" alt="community-manager-logo" class="logo">
                <div class="container-text">
                    <h1>
                        Community <br>
                        Manager
                    </h1>
                    <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi quas quisquam, aspernatur hic ratione consequuntur omnis autem asperiores nemo officia tempora deserunt dicta molestiae. Maxime accusamus inventore sit incidunt alias?
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'CommunityManager',
}
</script>

<style scoped>
.container {
  background-color: #141414;
  height: 100%;
}
.content {
    margin-right: 80px;
    border: solid 8px #EEBEAE;
}
.container-image {
    width: 100%;
}
.container-content {
    width: 100%;
}
.container-text {
    width: 30%;
    display: inline-block;
    vertical-align: top;
    font-family: 'Aileron', sans-serif;
    padding-left: 100px;
}
.container-text h1 {
    color: #EEBEAE;
    font-size: 70px;
    text-shadow: 8px 0px #4B413D;
}
.container-text p {
    color: white;
}
.logo {
    margin: 30px 30px 60px 60px;
}
</style>