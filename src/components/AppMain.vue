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
            <div id="jumbotron">

            </div>

            <div id="catalog">
                <div class="container">
                    <ComicsList/>
                </div>
            </div>
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
        min-height: 600px;
        padding: 50px 20px;
        background-color: #1C1C1C;
    }
</style>