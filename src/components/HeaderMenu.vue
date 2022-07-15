<template>
    <li>
        <a :href="url">
            {{text}}
        </a>
    </li>
</template>

<script>
export default {
    name: "HeaderMenu",
    props: {
        text: String,
        url: String
    }
}
</script>

<style lang="scss" scoped>
@import '@/style/common';
@import '@/style/variables';


li:first-child {
    border-bottom: 2px solid $primary-font-color;
}

li {
    font-weight: bold;
    line-height: 12px;
}
</style>