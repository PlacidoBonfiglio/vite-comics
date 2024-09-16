<script>
export default {
    data() {
        return {

        }
    }
}
</script>

<template>
    <footer>
        <section id="info" class="container">

        </section>

        <section id="links">
            <div class="container row links-box">

                <div class="sign-up">
                    <a href="#">SIGN-UP NOW!</a>
                </div>

                <div class="social row">
                    <div class="row">

                        <h2>FOLLOW US</h2>

                        <ul class="row">
                            <li>
                                <a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a>
                            </li>
                            <li>
                                <a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a>
                            </li>
                            <li>
                                <a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a>
                            </li>
                            <li>
                                <a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a>
                            </li>
                            <li>
                                <a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a>
                            </li>
                        </ul>

                    </div>
                </div>

            </div>
        </section>
    </footer>
</template>

<style scoped>

footer {
    background-image: url('../assets/img/footer-bg.jpg');
    background-size: cover;

    /* ! INFO */
    #info {
        min-height: 400px;
    }


    /* ! LINKS */
    #links {
        min-height: 150px;
        background-color: #303030;

        .links-box {
            height: 150px;
            align-items: center;

            .sign-up {
                width: 50%;

                a {
                    font-weight: bold;
                    color: white;
                    padding: 20px;
                    border: 3px solid #0C7CEC;
                    margin-left: 20px;

                    &:hover {
                        background-color: #535353;
                    }
                }
            }

            .social {
                width: 50%;
                justify-content: end;

                h2 {
                    color: #0C7CEC;
                    margin-right: 30px;
                }

                li {
                    margin-right: 20px;
                }
            }
        }
        
    }
}

</style>