<template>
    <div class="bg-linck">
        <div class="container d-flex justify-content-center">
            <div class="left3 d-flex">
                <div v-for="linck in linckList" :class="linck.class">
                    <h6>{{ linck.title }}</h6>
                    <ul>
                        <li v-for="lList in linck.list">
                            {{ lList }}
                        </li>
                    </ul>
                </div>
            </div>
            <div class="right3">     
            </div>
        </div>        
    </div>
</template>

<script>
    export default {
       name:'CompLinck',
       data(){
            return{
                linckList:  [
                    {
                        title: 'DC COMICS',
                        class: 'd-inline',
                        list: [
                          'Characters',
                            'Comics',
                            'Movies',
                            'TV',
                            'Games',
                            'Videos',
                            'News'
                        ]
                    },
                    {
                        title: 'SHOP',
                        class: 'd-inline',
                        list: [
                            'Shop DC',
                            'Shop DC Collectibles'
                        ]
                    },
                    {
                        title: 'DC',
                        class: 'd-block',
                        list: [
                            'Terms Of Use',
                            'Privacy policy (New)',
                            'Ad Choices',
                            'Advertising',
                            'Jobs',
                            'Subscriptions',
                            'Talent Workshops',
                            'CPSC Certificates',
                            'Ratings',
                            'Shop Help',
                            'Contact Us'
                        ]
                    },
                    {
                        title: 'SITES',
                        class: 'd-block',
                        list: [
                            'DC',
                            'MAD Magazine',
                            'DC Kids',
                            'DC Universe',
                            'DC Power Visa'
                        ]
                    }
                ]
            }
       } 
    }
</script>

<style lang="scss" scoped>
ul{
    list-style-type: none;
    margin: 0;
}
.bg-linck{
    background-image: url(/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: 100%;
    
}
.left3{
    width: 50%;
    padding-top: 20px;
    color: white;
}
.right3{
        width: 50%;
        background-image: url(/img/dc-logo-bg.png);
        background-repeat: no-repeat;
        background-position: right center;
        background-size: 100%;
       
    }
</style>