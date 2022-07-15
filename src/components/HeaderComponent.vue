<template>
  <header>
    <!-- navigation bar -->
    <nav class="row">
        <!-- logo -->
        <div class="ms_logo col">
            <img src="../assets/img/avada-bakery-logo-retina.png" alt="">
        </div>

        <!-- menu -->
        <ul class="ms_main_menu col">
            <HeaderMenu v-for="(link, index) in menuLinks" :key="index" :text="link.text" :url="link.url" />
        
            <li>
                <a href="#">
                    <i class="fa-solid fa-cart-shopping"></i>
                </a>
            </li>
        </ul>
    </nav>

  </header>
</template>

<script>
import HeaderMenu from '@/components/HeaderMenu.vue'

export default {
    name: "HeaderComponent",
    components: {
        HeaderMenu
    },
    data() {
    return {
      menuLinks: [
        {
          text: 'home',
          url: '#'
        },
        {
          text: 'shop',
          url: '#'
        },
        {
          text: 'about',
          url: '#'
        },
        {
          text: 'gallery',
          url: '#'
        },
        {
          text: 'locations',
          url: '#'
        }
        ,
        {
          text: 'journal',
          url: '#'
        },
        {
          text: 'contact',
          url: '#'
        },
        {
          text: 'my account',
          url: '#'
        },
        {
          text: <i class="fa-solid fa-cart-shopping"></i>,
          url: '#'
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
@import '@/style/common';
@import '@/style/variables';

header {
    background-image: url('../assets/img/hero-header-bakery.jpg');
    color: $primary-font-color;

    nav {
        align-items: flex-end;

        .ms_logo {
            img {
                height: 100px;
            }
        }

        ul {
            display: flex;
            justify-content: center;
            text-transform: uppercase;
            font-size: 14px;
        }
    }
}
</style>