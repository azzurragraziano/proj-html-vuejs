<template>
    <div class="row">
        <div class="col-4 ms_text_col">
            <span>
                fresh & tasty bakery every day
            </span>
            <h1 class="ms_title_font">
                The Perfect Fresh Bread
            </h1>
            <span>
                Architecto debitis laborum totam, voluptate officiis atque obcaecati provident! Ipsam, ducimus! Adipisci cumque autem id veniam dolor.
            </span>

            <a type="button" class="btn btn-light ms_btn">Explore our products</a>
        </div>

        <div class="col-8 ms_box_container">
            <div class="ms_box">
                <i class="fa-solid fa-face-grin"></i>
                <div>Demos</div>
            </div>

            <div class="ms_box">
                <span>$39</span>
                <div>On Sale</div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import '@/style/common';
@import '@/style/variables';

.row {
    .ms_text_col {
        padding: 10rem 0 14rem;

        span:first-child {
            text-transform: uppercase;
            font-size: 11px;
        }

        span {
            color: gray;
        }

        h1 {
            font-weight: 800;
        }

        .ms_btn {
            margin-top: 30px;
            font-size: 12px;
            color: $primary-font-color;
            font-weight: 600;
            border-radius: 5px;
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
            vertical-align: middle;
            width: 50px;
            height: 50px;
            color: black;
            font-size: 10px;
            border-radius: 5px;
            box-shadow: 1px 1px 19px 0px gray;
            margin-block: 3px;
            padding-block: 12px;
        }
    }
}
</style>