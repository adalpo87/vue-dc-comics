<template>
    <header>
        <div class="container">
            <div class="left">
                <a href="">
                    <img src="@/assets/img/dc-logo.png" alt="">
                </a>
              
            </div>
            <div class="right">
                <ul v-for="(link, index) in links" :key="index">
                    <li><a :href="link.url"
                           :class="{'active': link.current}"
                        >
                        {{link.text}}
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    name: 'HeaderDC',
    data(){
        return{
            links:[
                {
                    text: 'characters',
                    url: '#',
                    current: false
                },
                {
                    text: 'comics',
                    url: '#',
                    current: false
                },
                {
                    text: 'movies',
                    url: '#',
                    current: false
                },
                {
                    text: 'tv',
                    url: '#',
                    current: false
                },
                {
                    text: 'games',
                    url: '#',
                    current: false
                },
                {
                    text: 'collectibles',
                    url: '#',
                    current: false
                },
                {
                    text: 'videos',
                    url: '#',
                    current: false
                },
                {
                    text: 'fans',
                    url: '#',
                    current: false
                },
                {
                    text: 'news',
                    url: '#',
                    current: false
                },
                {
                    text: 'shop',
                    url: '#',
                    current: false
                }


            ]
        }
    }
}
</script>

<style lang="scss" scoped>

 @import '../assets/style/vars.scss';

    header{
        height: 115px;
        width: 100%;
            .container{
                width: $width-container;
                height: 100%;
                margin: auto;
                display: flex;
                justify-content: space-between;
                    .left{
                       
                        height: 100%;
                            a{
                                display: flex;
                                justify-content: flex-start;
                                align-items: center;
                                height: 100%;
                                     img{
                                     height: 70%;
                                     }
                            }
                    }
                    .right{
                        
                        height: 100%;
                        display: flex;
                        justify-content: flex-end;
                        
                            ul{
                                display: flex;
                                height: 100%;
                                justify-content: flex-end;
                                align-items: center;
                                    li{
                                            
                                            text-transform: uppercase;
                                            list-style: none;
                                            margin-left: 15px;
                                            height: 100%;
                                            line-height: 115px;
                                            ;
                                            &:hover,
                                            &.active{
                                                border-bottom: 3px solid $brand-color;
                                                }
                                            a{
                                                text-decoration: none;
                                                color: #292C21;
                                                font-size: 0.8rem;
                                            }
                            }
                    }  
                     
            }   
    }}
   
</style>