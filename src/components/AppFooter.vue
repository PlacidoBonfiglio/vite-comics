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
        <section id="info" class="container row">
            <div class="info-box row">
                <div class="row cols">
                    <div>
                        <h2>DC COMICS</h2>

                        <ul>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                        </ul>

                        <h2>SHOP</h2>

                        <ul>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                        </ul>
                    </div>

                    <div>
                        <h2>DC</h2>

                        <ul>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                            
                        </ul>
                    </div>

                    <div>
                        <h2>SITES</h2>

                        <ul>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                            <li>
                                <a href="#">blablabla</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>

            <div class="logo-bg">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
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
        padding: 50px 20px;

        .info-box {
            flex-basis: 60%;

            .cols {
                width: calc(100% / 3);
            
                h2 {
                    color: white;
                    margin-bottom: 20px;
                    margin-right: 60px;
                }

                li:last-child {
                    margin-bottom: 30px;
                }

                a {
                    color: grey;
                    line-height: 25px;

                    &:hover {
                        color: white;
                        border-bottom: 1px solid white;
                    }
                }
            }
        }

        .logo-bg {
            flex-basis: 40%;
        }
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

            /* ! SOCIAL */
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