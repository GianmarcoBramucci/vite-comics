<template>
    <nav class="navbar navbar-expand-lg">
        <div class="navbar-nav">
            <a class="nav-link" href="#" v-for="navString in navStrings">{{ navString }}</a>
        </div>
    </nav>
</template>

<script>
    export default {
        name: 'CompNav',
        data(){
            return{
                navStrings: [
                    'character',
                    'comics',
                    'movies',
                    'tv',
                    'games',
                    'collectibles',
                    'videos',
                    'fans',
                    'news',
                    'shop'
                ]
            }
        }
    }
</script>

<style lang="scss" scoped>
    a{
        text-transform: uppercase;
        font-size: 1.2rem;   
    }
</style>