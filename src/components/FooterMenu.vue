<template>
    <li>
        <a :href="url">
            {{text}}
        </a>
    </li>
</template>

<script>
export default {
    name: "FooterMenu",
    props: {
        text: String,
        url: String
    }
}
</script>

<style lang="scss" scoped>
@import '@/style/common';
@import '@/style/variables';



</style>