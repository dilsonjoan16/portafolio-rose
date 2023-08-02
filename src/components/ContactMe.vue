<template>
    <div class="container">
        <span class="spacer-line"></span>
        <div class="container-image">
            <img src="../assets/img/logo_rose.png" alt="logo" class="image">
        </div>
        <div class="container-content">
            <div class="container-text">
                <h1 class="content-text">
                    Contact Me:
                </h1>
                <img src="../assets/img/logo_contactos.png" alt="logo-contacts" class="contacts-logo">
                <div class="content-text-logos">
                    <h1>
                        <a href="mailto:rosanyelacontreras18@gmail.com">rosanyelacontreras18@gmail.com</a>
                    </h1>
                    <h1 style="margin-top: 100px;">
                        <a href="https://wa.me/584147320488">(+58) 414-7320488</a>
                    </h1>
                    <h1 style="margin-top: 100px;">
                        <a href="https://www.linkedin.com/in/rosanyela-contreras">linkedin.com/rosanyela-contreras</a>
                    </h1>
                </div>
            </div>
            <img src="../assets/img/profile.jpg" alt="profile" class="profile">
        </div>
        <div class="container-profile">
        </div>
    </div>
</template>

<script>
export default {
    name: 'ContactMe'
}
</script>

<style scoped>
.container {
  background-color: #141414;
  height: 100%;
}
.container-image {
    width: 100%;
}
.container-content {
    width: 100%;
}
.container-profile{
    width: 50%;
}
.container-text {
    display: inline-block;
}
.content-text-logos {
    display: inline-block;
    position: absolute;
    margin-left: 20px;
}
.content-text-logos h1 a {
    text-decoration: none;
    color: white;
    font-family: 'Aileron', sans-serif;
}
.content-text-logos h1 {
    font-size: 40px;
}
.content-text {
    text-align: left;
    font-family: 'Caveat', cursive;
    color: #EEBEAE;
    font-size: 130px;
    text-shadow: 14px 0px #4B413D;
    margin-left: 60px;
    margin-top: -30px;
    margin-bottom: 30px;
}
.profile {
    width: 30%;
    border-radius: 100%;
    margin-left: 25%;
}
.contacts-logo {
    margin-left: 60px;
    height: 400px;
}
.spacer-line {
    height: 92%;
}
</style>