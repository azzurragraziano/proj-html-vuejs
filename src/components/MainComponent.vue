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

                        <p class="ms_font">All our delectable pastries are backed fresh in our Kitchen every morning, and are made with all-natural, all organic ingredients.</p>
                    
                        <span>
                            <a type="button" class="btn btn_purple">Start Shopping</a>
                        </span>
                        
                    </div>

                    <!-- col with images -->
                    <div class="col-8">
                        <div class="row">
                            <div class="col">
                                <img src="../assets/img/choco-chip-cookies.jpg" alt="choco chip cookies">
                            </div>

                            <div class="col">
                                <img src="../assets/img/strawberry-jam-cookies.jpg" alt="choco chip cookies">
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
                    <div class="col-4">
                        <h2 class="ms_font">
                            Find a freshly backed <br> product perfect for you
                        </h2>

                        <span class="ms_description">
                            Corporis aut ut nulla natus reiciendis doloremque veritatis debitis odit dolorum ipsam dolores, quae vero, exercitationem dolorem.
                        </span>

                        <div>
                            <a type="button" class="btn btn_purple">Shop All Pruducts</a>
                        </div>
                    </div>

                    <div class="col-8">
                        <div class="row">
                            <div class="col">
                                <!-- image -->
                                <div class="card_image">
                                    <img src="../assets/img/choco-chip-cookies.jpg" alt="Choco Chip Cookies">
                                </div>

                                <!-- text -->
                                <div class="card_text">
                                    <h3 class="ms_font">Choco Chip Cookies</h3>
                                    <span>$19.00-$39.00</span>
                                </div>
                            </div>

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

                            <div class="col">
                                <!-- image -->
                                <div class="card_image">
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
    </main>
</template>

<script>
export default {
   
}
</script>

<style lang="scss" scoped>
@import '@/style/common';
@import '@/style/variables';

    // sfrutto il margin collapse per non scrivere troppo css ripetuto 
    section {
        margin-block: 9.4rem;    
    }

    .products {
        .ms_font {
            margin-block: 1rem 3rem;
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
</style>