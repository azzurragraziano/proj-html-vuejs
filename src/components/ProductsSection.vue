<template>
    <section class="products">
        <div class="ms_container">
            <div class="row">

                <!-- col with text -->
                <div class="col">
                    <div id="text">
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
                </div>

                <!-- left col with image -->
                <div class="col">
                    <div id="first-image">
                        <span class="chevron">
                            <i class="fa-solid fa-chevron-left"></i>
                        </span>

                        <div class="overlay">
                            <div class="ms_font">
                                choco chip cookies
                            </div>

                            <span>
                                Cookies, Pastries
                            </span>

                            <div class="price">
                                $19.00 $39.00
                            </div>
                        </div>
                    </div>
                </div>

                <!-- right col with image -->
                <div class="col">
                    <div id="second-image">
                        <span class="chevron">
                            <i class="fa-solid fa-chevron-right"></i>
                        </span>
                    </div>
                </div>
                
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "ProductsSection"
}
</script>

<style lang="scss" scoped>
@import '@/style/common';
@import '@/style/variables';
    
    .products {
        .col {
            height: 550px;

            .overlay {
                display: none;
                bottom: 100%;
            }

            .chevron {
                height: 100%;
                width: 18px;
                display: flex;
                align-items: center;

                i {
                    padding: 20px 8px;
                    background-color: rgba(86, 50, 139, 0.5);
                    color: white;
                }
            }  

            #first-image {
                background-image: url('../assets/img/choco-chip-cookies.jpg');
                background-position: center;
                background-size: cover;
                height: 100%;

                &:hover {
                    .overlay {
                        display: flex;
                        flex-direction: column;
                        justify-content: center;
                        align-items: center;
                        color: white;

                        .ms_font {
                            text-transform: capitalize;
                            font-size: 1.4rem;
                            margin-block: 0;
                            color: white;
                        }

                        span {
                            font-size: 0.7rem;
                        }

                        .price {
                            font-size: 1.2rem;
                            font-family: 'Work Sans', serif;
                        }
                    }
                }
            }

            #second-image {
                background-image: url('../assets/img/strawberry-jam-cookies.jpg');
                background-position: center;
                background-size: cover;
                height: 100%;

                position: relative;

                span {
                    position: absolute;
                    right: 10px;
                }
            }

            

            
        }
    }
</style>