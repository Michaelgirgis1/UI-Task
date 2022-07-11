<template>
    <div class="app-bar">
        <div class="app-bar__item">
            <img src="./../assets/app-bar/home.png" alt="app bar icon" srcset="">

        </div>
        <div class="app-bar__item">
            <img src="./../assets/app-bar/gift.png" alt="app bar icon" srcset="">


        </div>
        <div class="app-bar__item">
            <img src="./../assets/app-bar/money.png" alt="app bar icon" srcset="">


        </div>
        <div class="app-bar__item">
            <img src="./../assets/app-bar/chat.png" alt="app bar icon" srcset="">


        </div>
        <div class="app-bar__item">
            <img src="./../assets/app-bar/profile.png" alt="app bar icon" srcset="">

            
        </div>


    </div>
</template>

<style lang="scss">
 .app-bar {
    background-color: #1a1a1a;
    padding: 15px 0;
    position: fixed;
    bottom: -1px;
    z-index: 999999999;
    width: 100%;
    display: flex;
    justify-content: space-around;
    .app-bar__item {
        img {
            max-width: 35px;
        }
    }
 }
</style>