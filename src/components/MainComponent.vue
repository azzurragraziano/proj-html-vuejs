<template>
    <main>
        <!-- our profucts -->
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
    </main>
</template>

<script>
export default {
   
}
</script>

<style lang="scss" scoped>
@import '@/style/common';
@import '@/style/variables';

    .products {
        margin-block: 9.4rem;

        .ms_font {
            color: $primary-font-color;
            font-size: 1.6rem;
            font-weight: 900;
            margin-block: 1rem 3rem;
        }        
    }
</style>