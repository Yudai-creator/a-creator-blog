<template>
  <div>
    <NuxtWelcome />
    <vs-button>
        Hello World Vuesax + Nuxtjs
    </vs-button>
  </div>
</template>

<script setup>

// import Vuesax from 'vuesax3'
// import 'vuesax3/dist/vuesax.css' //Vuesax styles
// import { vsButton, vsSelect, vsPopup } from 'vuesax3'

useHead({
  script: [
    {
      src: 'https://cdn.jsdelivr.net/npm/vuesax/dist/vuesax.umd.js'
    }
  ],
  link: [
    {
      rel: 'stylesheet',
      href: 'https://cdn.jsdelivr.net/npm/vuesax/dist/vuesax.css'
    }
  ]
})

</script>
