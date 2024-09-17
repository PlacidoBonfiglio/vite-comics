<script>
import ComicsList from './ComicsList.vue';

export default {
    data() {
        return {
            
        }
    },
    components: {
        ComicsList
    }
}
</script>

<template>
    <main>
        <section>
            <section id="jumbotron">

            </section>

            <section id="catalog">
                <div class="container">
                    <div>
                        <ComicsList/>
                    </div>
                </div>
            </section>
        </section>
    </main>
</template>

<style lang="scss" scoped>
    #jumbotron {
        height: 550px;
        background-image: url('../assets/img/jumbotron.jpg');
        background-size: cover;
    }

    #catalog {
        min-height: 800px;
        padding-top: 80px;
        padding-left: 20px;
        padding-right: 20px;
        background-color: #1C1C1C;

        .container div {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
    }
</style>