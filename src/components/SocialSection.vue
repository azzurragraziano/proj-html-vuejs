<template>
    <section class="social">
        <div class="ms_container">
            <div class="row">
                <div class="col-3">
                    <figure>
                        <img src="../assets/img/social-1.jpg" alt="social 1">
                    </figure>
                </div>

                <div class="col-6">
                    <div class="ms_text_col">
                        <div class="ms_categories">
                            made for sharing
                        </div>

                        <div class="ms_font">
                            Let's stay in touch
                        </div>

                        <a href="#" class="btn btn_purple">
                            <i class="fa-brands fa-instagram"></i>
                            Follow Us
                        </a>
                    </div>
                </div>
                

                <div class="col-3">
                    <figure>
                        <img src="../assets/img/social-2.jpg" alt="social 2">
                    </figure>
                </div>

                <div class="col-3">
                    <figure>
                        <img src="../assets/img/social-3.jpg" alt="social 3">
                    </figure>
                </div>

                <div class="col-3">
                    <figure>
                        <img src="../assets/img/social-5.jpg" alt="social 5">
                    </figure>
                </div>

                <div class="col-3">
                    <figure>
                        <img src="../assets/img/social-4.jpg" alt="social 4">
                    </figure>
                </div>

                <div class="col-3">
                    <figure>
                        <img src="../assets/img/social-6.jpg" alt="social 6">
                    </figure>
                </div>

            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "SocialSection"
}
</script>

<style lang="scss" scoped>
@import '@/style/common';
@import '@/style/variables';

.social {
   .col-6 {
        padding-bottom: 16px;

        .ms_text_col {
            background-color: #f7f0f2;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100%;

            .ms_categories {
                font-size: 0.5rem;
            }

            .ms_font {
                font-size: 1.4rem;
                margin-block: 1rem;
            }

            .btn_purple {
                font-size: 9px;
                padding: 8px 18px;
            }
        }
    }        
}
</style>