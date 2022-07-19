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
                        <span>
                            <i class="fa-solid fa-chevron-left"></i>
                        </span>
                    </div>
                </div>

                <!-- right col with image -->
                <div class="col">
                    <div id="second-image">
                        <span>
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

            span {
                height: 100%;
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
            }

            #second-image {
                background-image: url('../assets/img/strawberry-jam-cookies.jpg');
                background-position: center;
                background-size: cover;
                height: 100%;

                span {
                    justify-content: flex-end;
                }
            }
        }
    }
</style>