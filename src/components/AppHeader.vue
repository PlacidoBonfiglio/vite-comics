<script>
export default {
    data() {
        return {
            navLinks: [
                {
                    label: "CHARACTERS",
                    url: "#",
                    active: false,
                },
                {
                    label: "COMICS",
                    url: "#",
                    active: true,
                },
                {
                    label: "MOVIES",
                    url: "#",
                    active: false,
                },
                {
                    label: "TV",
                    url: "#",
                    active: false,
                },
                {
                    label: "GAMES",
                    url: "#",
                    active: false,
                },
                {
                    label: "COLLECTIBLES",
                    url: "#",
                    active: false,
                },
                {
                    label: "FANS",
                    url: "#",
                    active: false,
                },
                {
                    label: "NEWS",
                    url: "#",
                    active: false,
                },
                {
                    label: "SHOP",
                    url: "#",
                    active: false,
                },
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
                    <li v-for="(navItem, index) in navLinks" :key="index" :class="{ active : navItem.active }">
                        <a href="navItem.url">{{ navItem.label }}</a>
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
            justify-content: space-between;

            a {
                padding-bottom: 62px;

                &.active {
                    color: #0C7CEC;
                    border-bottom: 5px solid #0C7CEC;
                }

                &:hover {
                color: #0C7CEC;
                border-bottom: 5px solid #0C7CEC;
                }
            }
        }
    }
}
</style>