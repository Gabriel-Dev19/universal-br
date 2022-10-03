<template>
  <div>
    <Home
      name-btn="Nossos serviços"
      hash-btn="servicos"
      title-principal="Agência de detetives particulares"
    />
    <CardsSwiper />
    <SwiperVertical />
    <Servicos />
    <Solutions />
    <Questions />
    <Faq />
    <Contato />
    <Footer />
  </div>
</template>

<script>
export default {
  head: {
    link: [
      { rel: 'alternate', href: 'https://universaldetetives.com.br/', hreflang: 'x-default' },
      { rel: 'alternate', href: 'https://universaldetetives.com.br/', hreflang: 'pt-br' },
      { rel: 'alternate', href: 'https://universaldetectives.pt/', hreflang: 'pt' }
    ]
  }
}
</script>
