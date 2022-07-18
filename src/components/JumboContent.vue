<template>
    <div class="row">
        <div class="col-4 ms_text_col">
            <span class="ms_categories">
                fresh & tasty bakery every day
            </span>
            <h1 class="ms_font">
                The Perfect Fresh Bread
            </h1>
            <div class="ms_description">
                Architecto debitis laborum totam, voluptate officiis atque obcaecati provident! Ipsam, ducimus! Adipisci cumque autem id veniam dolor.
            </div>

            <a type="button" class="btn btn-light btn_white">Explore our products</a>
        </div>

        <div class="col-8 ms_box_container">
            <div class="ms_box">
                <i class="fa-solid fa-face-grin"></i>
                <div>Demos</div>
            </div>

            <div class="ms_box">
                <span id="price"> <sup>$</sup>39</span>
                <div>On Sale</div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "JumboContent"
}
</script>

<style lang="scss" scoped>
@import '@/style/common';
@import '@/style/variables';

.row {
    .ms_text_col {
        padding: 10rem 0 14rem;

        h1 {
            font-weight: 800;
        }
    }

    .ms_box_container {
        display: flex;
        flex-direction: column;
        align-items: flex-end;
        padding-top: 50px;

        .ms_box {
            background-color: white;
            text-align: center;
            width: 50px;
            height: 50px;
            color: black;
            font-size: 8px;
            border-radius: 5px;
            box-shadow: 1px 1px 19px 0px gray;
            margin-block: 3px;
            padding-block: 6px;

            #price {
                color: #4caf50;
                font-size: 18px;
                font-weight: bold;
                font-family: Arial, Helvetica, sans-serif;
            }

            i {
                font-size: 18px;
                margin-block: 4px;
            }
        }
    }
}
</style>