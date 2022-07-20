<template>
    <main>
        <!-- our products -->
        <ProductsSection />

        <!-- corporate e weddings -->
        <section class="events">
            <div class="ms_container">

                <span class="ms_categories">
                    corporate e weddings
                </span>

                <h2 class="ms_font">
                    Baking Special Moments
                </h2>

                <div class="row gx-5">
                    <div class="col">
                        <div class="corporate">
                            <div class="overlay">
                                <div class="ms_categories">
                                    international bakery
                                </div>

                                <div class="ms_font">
                                    corporate events
                                </div>
                           

                                <!-- button -->
                                <div>
                                    <a href="#" class="btn btn_purple">Explore more</a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="col">
                        <div class="wedding">
                            
                            <div class="overlay">
                                <div class="ms_categories">
                                    private dining hall
                                </div>

                                <div class="ms_font">
                                    weddings & parties
                                </div>
                           

                                <!-- button -->
                                <div>
                                    <a href="#" class="btn btn_purple">Explore more</a>
                                </div>
                            </div>
                        </div>
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
                                <div id="choco-cookies" class="card_image">
                                    <!-- chevron -->
                                    <span id="left-chevron">
                                        <i class="fa-solid fa-chevron-left"></i>
                                    </span>

                                    <!-- image -->
                                    <!-- <img src="../assets/img/choco-chip-cookies.jpg" alt="Choco Chip Cookies"> -->

                                    <div class="overlay">
                                        <div>
                                            SELECT OPTIONS / QUICK VIEW
                                        </div>
                                    </div>
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
import ProductsSection from '@/components/ProductsSection.vue'
import BakeryProcess from '@/components/BakeryProcess.vue'
import SocialSection from '@/components/SocialSection.vue'

export default {
   name: "MainComponent",
   components: {
    ProductsSection,
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

    .events {
        text-align: center;

        .overlay {
            display: none;
        }

        .ms_categories {
            color: #e8e5e5;
        }


        .ms_font {
            text-transform: capitalize;
            font-size: 1.4rem;
            margin-block: 1.5rem;
            color: white;
        }
    
        .corporate {
            background-image: url('../assets/img/corporate-bg.jpg');
            background-size: cover;
            height: 610px;

            &:hover {

                background-image: url('../assets/img/corporate-hover-bg.jpg');

                .overlay {
                    display: flex;
                    flex-direction: column;
                    justify-content: center;
                    align-items: center;
                }
            }
        }

        .wedding {
            background-image: url('../assets/img/wedding-bg.jpg');
            background-size: cover;
            height: 610px;

            &:hover {

                background-image: url('../assets/img/wedding-hover-bg.jpg');

                .overlay {
                    display: flex;
                    flex-direction: column;
                    justify-content: center;
                    align-items: center;
                }
            }
        }
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

            .overlay {
                display: none;
            }

            .card_image {
                position: relative;
                font-size: 10px;
                color: white;

                &#choco-cookies {
                    background-image: url('../assets/img/choco-chip-cookies.jpg');
                    background-size: cover;
                    height: 265px;

                    &:hover {
                        .overlay {
                            display: flex;
                            justify-content: center;
                            align-items: center;
                        }
                    }
                }

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