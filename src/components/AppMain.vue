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
                    <div class="current-series">
                        <p>CURRENT SERIES</p>
                    </div>

                    <div>
                        <ComicsList/>
                    </div>

                    <div class="row load-button">
                        <button>LOAD MORE</button>
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
        padding-top: 80px;
        padding-left: 20px;
        padding-right: 20px;
        background-color: #1C1C1C;

        .current-series {
            position: relative;

            p {
                position: absolute;
                left: 0;
                top: -105px;
                color: white;
                background-color: #0C7CEC;
                font-size: 1.5rem;
                font-weight: bold;
                padding: 10px 20px;
            }
        }

        .load-button {
            justify-content: center;

            button {
                color: white;
                font-weight: bold;
                border: none;
                padding: 10px 60px;
                background-color: #0C7CEC;
                margin-bottom: 30px;

                &:hover {
                    background-color: rgb(114, 187, 255);
                    cursor: pointer;
                }
            }
        }

        .container div {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
    }
</style>