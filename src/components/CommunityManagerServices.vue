<template>
    <div class="container">
        <div class="content">
            <div class="container-image">
                <img src="../assets/img/logo_rose.png" alt="logo" class="image">
            </div>
            <div class="main-container">
                <div class="container-text">
                    <h1>
                        Community <br>
                        Manager services
                    </h1>
                    <h2>
                        Platforms
                    </h2>
                    <img src="../assets/img/community_manager_services.png" alt="community-manager-services-logo" width="40%">
                </div>
                <div class="container-list">
                    <ol class="order-list">
                        <li>
                            <h1>
                                Tax Preparation
                            </h1>
                            <span>
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam et quos deleniti, quam illum, aliquam tempora cum dolor maiores doloremque nulla. Asperiores reprehenderit consequuntur dolores corrupti doloremque tenetur adipisci aperiam?
                            </span>
                        </li>
                        <li>
                            <h1>
                                Start-up Package
                            </h1>
                            <span>
                                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Tempore dolorem consequatur deleniti dicta magnam optio a reiciendis qui libero corporis. Temporibus praesentium dolorum est itaque voluptas autem in corrupti laboriosam.
                            </span>
                        </li>
                        <li>
                            <h1>
                                Wealth Management
                            </h1>
                            <span>
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ut repellendus perferendis harum error eveniet minus temporibus, similique nisi ab nemo laboriosam voluptate doloremque voluptatibus, consectetur saepe labore fuga aperiam voluptas!
                            </span>
                        </li>
                    </ol>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'CommunityManagerServices'
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
.container-image {
    width: 100%;
    text-align: right;
}
.container-text {
    font-family: 'Aileron', sans-serif;
    padding-left: 60px;
}
.container-text h1 {
    font-size: 70px;
    text-shadow: 8px 0px #4B413D;
    color: #EEBEAE;
    width: fit-content;
}
.container-text h2 {
    color: white;
    font-size: 40px;
    width: fit-content;
}
.container-list {
    font-family: 'Aileron', sans-serif;
    color: white;
    padding-top: 30px;
}
.order-list {
  counter-reset: custom-counter;
  list-style-type: none;
  padding-left: 0;
}

.order-list li {
  position: relative;
  padding-left: 70px; 
  margin-bottom: 10px;
}

.order-list li::before {
  content: counter(custom-counter, decimal-leading-zero);
  counter-increment: custom-counter;
  position: absolute;
  left: 0;
  top: 0;
  font-size: 40px;
  color: #9B9B9B;
  font-weight: bold;
}
</style>