<template>
  <footer>
    <div class="ms_container">
        <div class="row">

            <!-- left col -->
            <div class="col-7 footer-menu">

                <!-- logo -->
                <div class="ms_logo">
                    <img src="../assets/img/avada-bakery-logo-retina.png" alt="logo">
                </div>

                <!-- footer menu -->
                <div class="ms_menu">
                    <ul>
                        <FooterMenu v-for="(link, index) in footerMenuLinks" :key="index" :text="link.text" :url="link.url" />

                        <li>
                            <a href="#">
                                <i class="fa-solid fa-cart-shopping"></i>
                                <span class="rounded">0</span>
                            </a>
                        </li>
                    </ul>
                </div>

                <!-- copyright -->
                <div>
                    <ul>
                        <li>
                            <a href="#"> &copy; Copyright 2012 - 2020 </a>|
                        </li>

                        <li>
                            <a href="#"> Avada Theme by ThemeFusion </a>|
                        </li>

                        <li>
                            <a href="#"> All Rights Reserved </a>|
                        
                        </li>

                        <li>
                            <a href="#"> Powerred by WordPress</a>
                        </li>
                    </ul>
                </div>
            </div>

            <!-- right col -->
            <div class="col-5 subscribe">

                <div class="ms_font">
                    Subscribe to our Newsletter
                </div>

                <div>
                    <input type="email" name="email" id="email" placeholder="Enter email address*">
                    <label for="email"></label>
                    <button class="btn btn_purple">Subscribe</button>
                </div>

                <ul class="social">
                    <li>
                        <a href="#">
                            <i class="fa-brands fa-instagram"></i>
                        </a>
                    </li>

                    <li>
                        <a href="#">
                            <i class="fa-brands fa-twitter"></i>
                        </a>
                    </li>

                    <li>
                        <a href="#">
                            <i class="fa-brands fa-facebook-f"></i>
                        </a>
                    </li>

                    <li>
                        <a href="#">
                            <i class="fa-brands fa-pinterest-p"></i>
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
  </footer>
</template>

<script>
import FooterMenu from '@/components/FooterMenu.vue'

export default {
    name: "FooterComponent",
    components: {
        FooterMenu
    }, 
    data() {
        return {
            footerMenuLinks: [
                {
                text: 'shop',
                url: '#'
                },
                {
                text: 'about',
                url: '#'
                },
                {
                text: 'gallery',
                url: '#'
                },
                {
                text: 'locations',
                url: '#'
                }
                ,
                {
                text: 'journal',
                url: '#'
                },
                {
                text: 'contact',
                url: '#'
                },
                {
                text: 'orders',
                url: '#'
                }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import '@/style/common';
@import '@/style/variables';

    .footer-menu{
        .ms_logo {
            img {
                width: 200px;
            }
        }

        .ms_menu {
            ul {
                text-transform: capitalize;
                padding-block: 3rem 5rem;
                padding-left: 0;
                display: flex;
                justify-content: space-between;

                li {
                    color: $primary-font-color;

                    &:last-child {
                        display: flex;

                        i {
                            padding-right: 5px;
                        }

                        .rounded {
                            background-color: #f0edf5;
                            display: inline-block;
                            width: 30px;
                            height: 30px;
                            border-radius: 50%; //doesn't work
                            text-align: center;
                            line-height: 30px;
                        }
                    }
                }
            }
        }

        div:last-child {
            color: gray;
            text-decoration: none;
            font-size: 0.6rem;

            ul {
                padding-left: 0;

                li {
                    display: inline;
                    margin: 0;
                }
            }
        }
    }

    .subscribe {
        display: flex;
        flex-direction: column;
        align-items: flex-end;

        input {
            padding: 0.7rem 8rem 0.7rem 0.5rem;
            border-radius: 5px;
            margin-right: 1rem;
            border: 1px solid lightgray;
            font-size: 0.8rem;
        }

        .social {
            color: $primary-font-color;
            display: flex;
            margin-top: 8rem;
            margin-bottom: 3rem;

            li {
                padding-inline: 0.7rem;
            }
        }
    }
</style>