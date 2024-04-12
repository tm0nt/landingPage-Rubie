<script setup lang="ts">
useHead({
  title: 'Somos Rubie | Impulsione sua marca online',
  meta: [
    { name: 'description', content: 'Somos uma agência especializada em soluções digitais, combinando expertise em programação e marketing para impulsionar o sucesso dos nossos clientes. Desde desenvolvimento de software personalizado até campanhas de marketing digital, estamos aqui para transformar sua presença online. Conheça nossos serviços agora!' },
  ],
  link: [
    { rel: 'icon', type: 'image/png', href: '/logo.png' }
  ],
})
</script>
<template>
    <div>
        <SectionsHomeHeroSection/>
        <SectionsHomeLatestPodcast/>
        <SectionsHomePopularPodcasts/>
        <SectionsAboutPodux/>
        <SectionsWhyUs/>
        <SectionsCallToAction/>
    </div>
</template>