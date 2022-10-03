<template>
  <div>
    <Home
      name-btn="Nossos serviços"
      hash-btn="servicos"
      title-principal="Serviços de detetive particular"
    />
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
      { rel: 'alternate', href: 'https://universaldetetives.com.br/servicos', hreflang: 'x-default' },
      { rel: 'alternate', href: 'https://universaldetetives.com.br/servicos', hreflang: 'pt-br' },
      { rel: 'alternate', href: 'https://universaldetectives.pt/servicos', hreflang: 'pt' }
    ]
  }
}
</script>
