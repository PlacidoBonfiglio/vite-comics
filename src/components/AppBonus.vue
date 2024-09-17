<script>
export default {
    data() {
        return {
            bonusLinks: [
                {
                    imgUrl: '../assets/img/buy-comics-digital-comics.png',
                    imgAlt: 'digital comics',
                    name: 'DIGITAL COMICS'
                },
                {
                    imgUrl: '../assets/img/buy-comics-merchandise.png',
                    imgAlt: 'merchandise',
                    name: 'DC MERCHANDISE'
                },
                {
                    imgUrl: '../assets/img/buy-comics-subscriptions.png',
                    imgAlt: 'subscription',
                    name: 'SUBSCRIPTION'
                },
                {
                    imgUrl: '../assets/img/buy-comics-shop-locator.png',
                    imgAlt: 'shop locator',
                    name: 'COMIC SHOP LOCATOR'
                },
                {
                    imgUrl: '../assets/img/buy-dc-power-visa.svg',
                    imgAlt: 'power visa',
                    name: 'DC POWER VISA'
                },
            ]
        }
    }
}
</script>

<template>
   <section id="bonus">
    <div class="container">
        <ul class="row">
            <li v-for="(bonus, index) in bonusLinks" :key="index">
                <a href="#"><img :src="bonus.imgUrl" :alt="bonus.imgAlt"></a>
                <a href="#">{{bonus.name}}</a>
            </li>
        </ul>
    </div>
    
   </section>
</template>

<style scoped>
    #bonus {
        height: 200px;
        background-color: #0C7CEC;
        position: relative;
        z-index: 1;

        ul {
            height: 200px;
            justify-content: space-around;
            align-items: center;


            img {
            height: 60px;
            }

            a {
            color: white;
            }
        }
    }

        
</style>