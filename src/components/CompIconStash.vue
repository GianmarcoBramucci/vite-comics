<template>
    <div class="bg-primary">
        <div class="container">
            <div class="d-flex">
                <div v-for="iconText in iconsTexts" class="h-100">
                    <img :src="iconText.img" alt="">
                    <span>{{iconText.text}}</span>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'CompIconStash',
        data(){
            return{
                iconsTexts:[
                    {
                        img: '/img/buy-comics-digital-comics.png',
                        text:'digital comics'
                    },
                    {
                        img: '/img/buy-comics-merchandise.png',
                        text:'DC merchandise'
                    },
                    {
                        img: '/img/buy-comics-subscriptions.png',
                        text:'subscriptions'
                    },
                    {
                        img:'/img/buy-comics-shop-locator.png',
                        text: 'comics shop locator'
                    },
                    {
                        img: '/img/buy-dc-power-visa.svg',
                        text:'dc power visa'
                    }
                ]
            }
        }
    }
</script>

<style lang="scss" scoped>
    img{
        height: 65px;
        width: 55px;
        padding: 5px;

    }
    span{
        color: white;
    }
</style>