<script>
export default {
    data() {
        return {
            bonusLinks: [
                {
                    img: '<img src="../assets/img/buy-comics-digital-comics.png" alt="digital comics">',
                    name: 'DIGITAL COMICS'
                },
                {
                    img: '<img src="../assets/img/buy-comics-merchandise.png" alt="merchandise">',
                    name: 'DC MERCHANDISE'
                },
                {
                    img: '<img src="../assets/img/buy-comics-subscriptions.png" alt="subscription">',
                    name: 'SUBSCRIPTION'
                },
                {
                    img: '<img src="../assets/img/buy-comics-shop-locator.png" alt="shop locator">',
                    name: 'COMIC SHOP LOCATOR'
                },
                {
                    img: '<img src="../assets/img/buy-dc-power-visa.svg" alt="power visa">',
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
            <li v-for="bonus in bonusLinks">
                <a href="#">{{ bonus.img }} {{ bonus.name }}</a>
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