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
                                <a href="#">Characters</a>
                            </li>
                            <li>
                                <a href="#">Comics</a>
                            </li>
                            <li>
                                <a href="#">Movies</a>
                            </li>
                            <li>
                                <a href="#">TV</a>
                            </li>
                            <li>
                                <a href="#">Games</a>
                            </li>
                            <li>
                                <a href="#">Videos</a>
                            </li>
                            <li>
                                <a href="#">News</a>
                            </li>
                        </ul>

                        <h2>SHOP</h2>

                        <ul>
                            <li>
                                <a href="#">Shop DC</a>
                            </li>
                            <li>
                                <a href="#">Shop DC Collectibles</a>
                            </li>
                        </ul>
                    </div>

                    <div>
                        <h2>DC</h2>

                        <ul>
                            <li>
                                <a href="#">Terms Of Use</a>
                            </li>
                            <li>
                                <a href="#">Privacy policy (New)</a>
                            </li>
                            <li>
                                <a href="#">Ad Choices</a>
                            </li>
                            <li>
                                <a href="#">Advertising</a>
                            </li>
                            <li>
                                <a href="#">Jobs</a>
                            </li>
                            <li>
                                <a href="#">Subscriptions</a>
                            </li>
                            <li>
                                <a href="#">Talent Workshops</a>
                            </li>
                            <li>
                                <a href="#">CPSC Certificates</a>
                            </li>
                            <li>
                                <a href="#">Ratings</a>
                            </li>
                            <li>
                                <a href="#">Shop Help</a>
                            </li>
                            <li>
                                <a href="#">Contact Us</a>
                            </li>
                        </ul>
                    </div>

                    <div>
                        <h2>SITES</h2>

                        <ul>
                            <li>
                                <a href="#">DC</a>
                            </li>
                            <li>
                                <a href="#">MAD Magazine</a>
                            </li>
                            <li>
                                <a href="#">DC Kids</a>
                            </li>
                            <li>
                                <a href="#">DC Universe</a>
                            </li>
                            <li>
                                <a href="#">DC Power Visa</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>

            <div class="logo-bg row">
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
        height: 450px;
        padding: 50px 20px;

        .info-box {
            flex-basis: 40%;

            .cols {
                width: 100%;   

                div{
                    width: calc(100% / 3);


                    h2 {
                    color: white;
                    margin-bottom: 20px;
                    font-size: 1.3rem;
                    }

                    li:last-child {
                    margin-bottom: 30px;
                    }

                    a {
                    color: grey;
                    line-height: 25px;
                    font-size: 0.9rem;

                        &:hover {
                            color: white;
                            border-bottom: 1px solid white;
                        }
                    }
                }
            
                
            }
        }

        .logo-bg {
            flex-basis: 60%;
            justify-content: end;
            position: relative;

            img {
                position: absolute;
                top: -110px;

            }
        }
    }


    /* ! LINKS */
    #links {
        min-height: 150px;
        background-color: #303030;
        position: relative;
        z-index: 1;

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