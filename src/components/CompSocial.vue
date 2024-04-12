<template>
    <div class="sfondo">
        <div class="container d-flex justify-content-between">
            <div>
                <button>SIGN-UP NOW!</button>
            </div>
            <div>
                <span>FOLLOW US</span>
                <span v-for="img in imgPath">
                    <img :src="img" alt="">
                </span>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'CompSocial',
        data(){
            return{
                imgPath:[
                    '/img/footer-facebook.png',
                    '/img/footer-periscope.png',
                    '/img/footer-pinterest.png',
                    '/img/footer-twitter.png',
                    '/img/footer-youtube.png'
                ]
            }
        }
    }
</script>

<style lang="scss" scoped>
span{
    margin-left: 5px;
}
.sfondo{
    background-color: grey;
    padding-top: 20px;
    padding-bottom: 20px;
} 

</style>