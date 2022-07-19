<template>
    <section class="bakery-process">
        <div class="ms_container">
            <div class="row g-4">

                <!-- first bakery process col -->
                <div class="col-12">
                    <div id="first"> 
                        <!-- overlay -->
                        <div class="overlay">
                            <!-- card -->
                            <div class="ms_card">

                                <!-- text top -->
                                <div class="text_top">
                                    <div class="top_left">
                                        Tell us what you have in mind
                                    </div>

                                    <div class="top_right">
                                        01
                                    </div>
                                </div>

                                <!-- text bottom -->
                                <div class="text_bottom">

                                    <!-- right -->
                                    <div class="bottom_right">
                                        <div class="ms_categories">
                                            manual ingredients selection
                                        </div>

                                        <p>
                                            Cras consequat lectus vestibulum tortor pulvinar, quis euismond nisl varius. Ut eu laoreet ex. Aliquam erat volutpat. Nullam quis sagittis nibh. Morbi consectetur ultricies ante ac congue. Donec lorem erat, finibus in velit placerat, rutrum augue.
                                        </p> 
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- second bakery process col -->
                <div class="col-6">
                    <div id="second">
                        <!-- overlay -->
                        <div class="overlay">
                            <!-- card -->
                            <div class="ms_card">

                                <!-- text top -->
                                <div class="text_top"> 
                                    <!-- left -->
                                    <div class="top_left">
                                        We Start Baking
                                    </div>

                                    <!-- right -->
                                    <div class="top_right">
                                        02
                                    </div>
                                </div>

                                <!-- text bottom -->
                                <div class="text_bottom">

                                    <!-- left -->
                                    <div class="bottom_left">
                                        <div class="ms_categories">
                                            sweet & delicious
                                        </div>

                                        <p>
                                            Cras consequat lectus vestibulum tortor pulvinar, quis euismond nisl varius. Ut eu laoreet ex. Aliquam erat volutpat. Nullam quis sagittis nibh. Morbi consectetur ultricies ante ac congue. Donec lorem erat, finibus in velit placerat.
                                        </p> 
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- text bakery process col -->
                <div class="col-6">
                    <div id="text">
                        <div class="ms_card_text">
                            <div class="ms_categories">
                                don't just take our word for it
                            </div>

                            <div class="ms_font">
                                "Finally found an alternative to the mass produced products.
                                Something that incorporates real organic ingredients, 
                                nutrient dense wellness while promoting sustainability and activity."
                            </div>

                            <div class="ms_categories author">
                                Rachel Cooper, Founder
                            </div>
                        </div>
                    </div>
                </div>

                <!-- third bakery process col -->
                <div class="col-12">
                    <div id="third">
                        <!-- overlay -->
                        <div class="overlay">
                            <!-- card -->
                            <div class="ms_card">

                                <!-- text top -->
                                <div class="text_top">
                                    <div class="top_left">
                                        Tell us what you have in mind
                                    </div>

                                    <div class="top_right">
                                        03
                                    </div>
                                </div>

                                <!-- text bottom -->
                                <div class="text_bottom">

                                    <!-- right -->
                                    <div class="bottom_right">
                                        <div class="ms_categories">
                                            baked to order & gift wrapped
                                        </div>

                                        <p>
                                            Cras consequat lectus vestibulum tortor pulvinar, quis euismond nisl varius. Ut eu laoreet ex. Aliquam erat volutpat. Nullam quis sagittis nibh. Morbi consectetur ultricies ante ac congue. Donec lorem erat, finibus in velit placerat, rutrum augue.
                                        </p> 
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "BakeryProcess"
}
</script>

<style lang="scss" scoped>
@import '@/style/common';
@import '@/style/variables';    

    .bakery-process {
        .row {
            display: flex;
            flex-wrap: wrap;
            color: white;

            .overlay {
                position: relative;
                left: 50%;
                top: 0;
                transform: translate(-50%, 0);
                background-color: rgba(0, 0, 0, 0.4);
                width: 100%;
                height: 100%;

                .ms_card {
                    height: 100%;
                    padding: 4rem;

                    .ms_categories {
                        color: #d1d0c2;
                        margin-bottom: 1rem;
                    }
                    
                    .text_top {
                        display: flex;
                        align-items: flex-start;
                        justify-content: space-between;

                        .top_left {
                            font-family: 'Playfair Display', serif;
                            font-weight: bold;
                            font-size: 2rem;
                            line-height: 2.5rem;
                        }

                        .top_right {
                            font-family: 'Work Sans', sans-serif;
                            font-weight: 100;
                            font-size: 3.5rem;
                            line-height: 3.5rem;
                        }
                    }

                    .text_bottom {
                        display: flex;
                        align-items: flex-end;
                        justify-content: flex-end;
                        height: 100%;
                        font-size: 0.8rem;
                        padding-bottom: 2rem;
                        
                        .bottom_right
                        {
                            width: 400px;
                        }
                    }
                }
            } 

            .col-12 {
                height: 534px;

                #first {
                    background-image: url('../assets/img/bakery-process-1.jpg');
                    background-size: cover;
                    height: 100%;
                }

                #third {
                    background-image: url('../assets/img/bakery-process-3.jpg');
                    background-size: cover;
                    background-position: center;
                    height: 100%;
                }            
            }

            .col-6 {
                height: 500px;

                #second {
                    background-image: url('../assets/img/bakery-process-2.jpg');
                    background-size: cover;
                    background-position: right;
                    height: 100%;
                    

                    .text_bottom {
                        justify-content: flex-start;

                        .bottom_left
                        {
                            width: 280px;
                        }
                    }
                }

                #text {
                    background-color: #f7f0f2;
                    height: 100%;

                    .ms_card_text {
                        height: 100%;
                        padding: 4rem;

                        .ms_font {
                            font-size: 1.8rem;
                            margin-block: 2rem;
                        }

                        .author {
                            text-transform: capitalize;
                        }
                    }
                }
            }
        }
    }
</style>