<script>
export default {
    data() {
        return {
            navLinks: [
                    "CHARACTERS",
                    "COMICS",
                    "MOVIES",
                    "TV",
                    "GAMES",
                    "COLLECTIBLES",
                    "FANS",
                    "NEWS",
                    "SHOP",
            ]
        }
    }
}
</script>

<template>
    <header>
        <section id="navbar" class="row container">
            <div class="div-logo">
                <a><img src="../assets/img/dc-logo.png" alt="dc main logo"></a>
            </div>

            <div class="div-ul">
                <ul class="row">
                    <li v-for="navItem in navLinks">
                        <a href="#">{{ navItem }}</a>
                    </li>
                </ul>
            </div>
        </section>
    </header>
</template>

<style scoped>
section {
    height: 150px;
    align-items: center;

    .div-logo {
        width: 30%;

        img {
            cursor: pointer;
            margin-left: 20px
        }
    }

    .div-ul {
        width: 70%;
        font-weight: bold;

        ul {
            flex-wrap: wrap;

            li {
            margin-right: 2rem;

                a {
                    padding-bottom: 60px;

                    &:hover {
                    color: #0C7CEC;
                    border-bottom: 5px solid #0C7CEC;
                    }

                }
            }
        }
    }
}
</style>