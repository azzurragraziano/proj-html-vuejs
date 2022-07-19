<template>
    <main>
        <!-- our products -->
        <section class="products">
            <div class="ms_container">
                <div class="row">

                    <!-- col with text -->
                    <div class="col-4">

                        <span class="ms_categories">
                            our products
                        </span>

                        <p class="ms_font">
                            All our delectable pastries are backed fresh in our Kitchen every morning, and are made with all-natural, all organic ingredients.
                        </p>

                        <!-- button -->
                        <span>
                            <a type="button" class="btn btn_purple">Start Shopping</a>
                        </span>

                    </div>

                    <!-- col with images -->
                    <div class="col-8">
                        <div class="row">

                            <!-- left col -->
                            <div class="col">
                                <div class="ms_card">
                                    <!-- chevron -->
                                    <span>
                                        <i class="fa-solid fa-chevron-left"></i>
                                    </span>

                                    <!-- image -->
                                    <img src="../assets/img/choco-chip-cookies.jpg" alt="choco chip cookies">
                                </div>
                            </div>

                            <!-- right col -->
                            <div class="col">
                                <div class="ms_card">
                                    <!-- chevron -->
                                    <span>
                                        <i class="fa-solid fa-chevron-right"></i>
                                    </span>

                                    <!-- image -->
                                    <img src="../assets/img/strawberry-jam-cookies.jpg" alt="strawberry jam cookies">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- corporate e weddings -->
        <section class="corp-wed">
            <div class="ms_container">

                <span class="ms_categories">
                    corporate e weddings
                </span>

                <h2 class="ms_font">
                    Baking Special Moments
                </h2>

                <div class="row gx-5">
                    <div class="col">
                        <img src="../assets/img/wedding-bg.jpg" alt="corporate">
                    </div>

                    <div class="col">
                        <img src="../assets/img/wedding-bg.jpg" alt="weddings">
                    </div>
                </div>
            </div>
        </section>

        <!-- some shopping -->
        <section class="shopping">
            <div class="ms_container">
                <div class="row">

                    <!-- col with text -->
                    <div class="col-4">
                        <h2 class="ms_font">
                            Find a freshly backed <br> product perfect for you
                        </h2>

                        <span class="ms_description">
                            Corporis aut ut nulla natus reiciendis doloremque veritatis debitis odit dolorum ipsam dolores, quae vero, exercitationem dolorem.
                        </span>

                        <!-- button -->
                        <div>
                            <a type="button" class="btn btn_purple">Shop All Pruducts</a>
                        </div>
                    </div>

                    <div class="col-8">
                        <div class="row">

                            <!-- first product -->
                            <div class="col">
                                <!-- image -->
                                <div class="card_image">
                                    <!-- chevron -->
                                    <span id="left-chevron">
                                        <i class="fa-solid fa-chevron-left"></i>
                                    </span>

                                    <!-- image -->
                                    <img src="../assets/img/choco-chip-cookies.jpg" alt="Choco Chip Cookies">
                                </div>

                                <!-- text -->
                                <div class="card_text">
                                    <h3 class="ms_font">Choco Chip Cookies</h3>
                                    <span>$19.00-$39.00</span>
                                </div>
                            </div>

                            <!-- second product -->
                            <div class="col">
                                <!-- image -->
                                <div class="card_image">
                                    <img src="../assets/img/strawberry-jam-cookies.jpg" alt="Strawberry Jam Cookies">
                                </div>

                                <!-- text -->
                                <div class="card_text">
                                    <h3 class="ms_font">Strawberry Jam Cookies</h3>
                                    <span>$24.00-$62.00</span>
                                </div>
                            </div>

                            <!-- third product -->
                            <div class="col">
                                <!-- image -->
                                <div class="card_image">
                                    <img src="../assets/img/strawberry-donut.jpg" alt="Strawberry Donut">
                                </div>

                                <!-- text -->
                                <div class="card_text">
                                    <h3 class="ms_font">Strawberry Donut</h3>
                                    <span>$24.00-$42.00</span>
                                </div>
                            </div>

                            <!-- fourth product -->
                            <div class="col">
                                <!-- image -->
                                <div class="card_image">
                                    <!-- chevron -->
                                    <span id="right-chevron">
                                        <i class="fa-solid fa-chevron-right"></i>
                                    </span>

                                    <!-- image -->
                                    <img src="../assets/img/perfect-macarons.jpg" alt="Perfect Macarons">
                                </div>

                                <!-- text -->
                                <div class="card_text">
                                    <h3 class="ms_font">Perfect Macarons</h3>
                                    <span>$18.00-$52.00</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- bakery process -->
        <BakeryProcess/>

        <!-- locations -->
        <section class="locations">
            <div class="ms_container">

                <!--  info -->
                <div class="ms_info">
                    <div class="ms_categories">
                        locations
                    </div>

                    <h2 class="ms_font">
                        Visit our Bakeries
                    </h2>
                </div>

                <div class="row">

                    <!-- col -->
                    <div id="lightblue" class="col">

                        <!-- card -->
                        <div class="ms_card">

                            <!-- image card -->
                            <div class="image-card">
                                <img src="../assets/img/new-york-bk.jpg" alt="New York bakery">
                            </div>

                            <!-- text card -->
                            <div class="text_card">

                                <!-- city -->
                                <h2 class="ms_font">
                                    New York
                                </h2>

                                <!-- other info -->
                                <div class="row">

                                    <!-- tel number -->
                                    <div class="col">
                                        <div class="ms_categories">
                                            call us
                                        </div>

                                        <div class="ms_categories">
                                            1.800.458.556
                                        </div>
                                    </div>

                                    <!-- working hours -->
                                    <div class="col">
                                        <div class="ms_categories">
                                            open all week
                                        </div>

                                        <div class="ms_categories">
                                            9:00 am - 6:00 pm
                                        </div>
                                    </div>

                                    <!-- btn -->
                                    <div class="col">
                                        <a href="#" class="btn btn-light btn_white">View Map</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- col -->
                    <div id="beige" class="col">

                        <!-- card -->
                        <div class="ms_card">

                            <!-- image card -->
                            <div class="image-card">
                                <img src="../assets/img/london-bk.jpg" alt="London bakery">
                            </div>

                            <!-- text card -->
                            <div class="text_card">

                                <!-- city -->
                                <h2 class="ms_font">
                                    London
                                </h2>

                                <!-- other info -->
                                <div class="row">

                                    <!-- tel number -->
                                    <div class="col">
                                        <div class="ms_categories">
                                            call us
                                        </div>

                                        <div class="ms_categories">
                                            1.800.458.556
                                        </div>
                                    </div>

                                    <!-- working hours -->
                                    <div class="col">
                                        <div class="ms_categories">
                                            open all week
                                        </div>

                                        <div class="ms_categories">
                                            9:00 am - 6:00 pm
                                        </div>
                                    </div>

                                    <!-- btn -->
                                    <div class="col">
                                        <a href="#" class="btn btn-light btn_white">View Map</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- social -->
        <SocialSection/>

        <!-- banner -->
        <section class="banner">
            <div class="text">

                <div class="ms_categories">
                    try our seasonal products
                </div>

                <div class="ms_font">
                    Order for pick-up or delivery to your home
                </div>

                <a href="#" class="btn btn-light btn_white">Shop Now</a>
            </div>
        </section>

    </main>
</template>

<script>
import BakeryProcess from '@/components/BakeryProcess.vue'
import SocialSection from '@/components/SocialSection.vue'

export default {
   name: "MainComponent",
   components: {
    BakeryProcess,
    SocialSection
   }
}
</script>

<style lang="scss" scoped>
@import '@/style/common';
@import '@/style/variables';

    section {
        margin-top: 9.4rem;
    }

    .products {
        .ms_font {
            margin-block: 1rem 3rem;
            font-size: 1.4rem;
        }

        .col {
            position: relative;
            font-size: 10px;
            color: white;

            span {
                position: absolute;
                top: 45%;
                
                i {
                    padding: 20px 8px;
                    background-color: rgba(86, 50, 139, 0.5);
                }                
            } 
            &:first-child {
                span {
                    left: 13px;          
                }
            }

            &:last-child {
                span {
                    right: 13px;    
                }
            }
        }
    }

    .corp-wed {
        text-align: center;
    }

    .shopping {
        .col-4 {
            text-align: center;
            margin-top: 3rem;

            h2 {
                margin-block: 1rem;
            }

            div
            {
                margin-block: 1rem;
            }
        }

        .col-8 {
            .card_image {
                position: relative;
                font-size: 10px;
                color: white;

                span {
                    position: absolute;
                    top: 45%;
                    
                    i {
                        padding: 20px 8px;
                        background-color: rgba(86, 50, 139, 0.5);
                    }       
                    
                    &#left-chevron {
                        left: 0;          
                    }
                    
                    &#right-chevron {
                        right: 0;    
                    }
                    
                } 

                
            }

            .card_text {
                text-align: center;

                .ms_font {
                    font-size: 1rem;
                    margin-block: 1rem;
                }

                span {
                    font-size: 0.8rem;
                    color: $primary-font-color;
                }
            }
        }
    }

    .locations {
        .ms_info {
            text-align: center;
        }

        .col {
            padding: 0;
            text-align: center;

            &#lightblue {
                background-color: #f1f9fb;
            }

            &#beige {
                background-color: #faf3e3;
            }

            .ms_card {
                .text_card {
                    padding: 1rem 3rem 2rem;

                    .col {
                        .ms_categories:first-child {
                            font-size: 9px;
                        }

                        .btn_white {
                            margin-top: 0;
                        }
                    }
                }
            }
        }
    }

    .banner {
        background-image: url('../assets/img/call-to-action-bg.jpg');
        background-size: cover;
        background-position: top;

        .text {
            margin: 10rem;
            padding-block: 3.5rem;
            width: 530px;

            .ms_font {
                color: white;
                font-size: 2rem;
            }
        }
    }
</style>