<template>
  <section>
    <Home
      name-btn="Sobre a agência"
      hash-btn="sobre"
      title-principal="Sobre a universal detetives"
    />
    <div id="sobre" class="container">
      <HeaderSections
        style="margin-top: 150px"
        :is-reverse="true"
        :img="require('../../assets/img/linhas-investigacao.webp')"
        title-badge="sobre nós"
        title-header="Sobre a agência universal detetives"
        subtitle="Somos uma agência comprometida com a excelência e a dedicação"
        description="A Universal Agência de Detetives, é uma agência com experiência de 21 anos no ramo de investigação
        particular. Contamos com um conjunto de profissionais dedicados e qualificados."
      />
      <div class="container-text">
        <h2 class="azul mb-3">
          Sobre nós
        </h2>
        <p>
          A Universal Agência de Detetives, é uma agência com experiência de 21 anos no ramo de investigação particular. Contamos com um conjunto de profissionais dedicados e qualificados para atuar nas mais diversas áreas da investigação particular de formar a manter sigilo e discrição total da sua identidade.
        </p>
        <p>
          Dispomos de uma equipe de trabalho multidisciplinar, profissional e competente. Temos uma vasta gama de serviços de investigação profissionais destinados a empresas e particulares.
        </p>
        <p>
          Estamos sempre ao seu dispor, atuamos sempre com rigor e sigilo, todos os processos são tratados com a máxima confidencialidade.
        </p>
        <p>
          Se pretende iniciar um projeto de investigação particular, entre em contato conosco para que possamos desenvolver uma estratégia que beneficie este processo de modo a obter os resultados pretendidos na conclusão desta investigação.
        </p>
        <h2 class="azul mb-3">
          Código de Ética
        </h2>
        <p>
          A atuação dos detetives da Universal Agência de Detetives Particulares pauta-se em permanência pelo rigoroso sigilo dado as solicitações dos clientes, não aceitando igualmente todo o tipo de investigação que indicie e devasse a privacidade de terceiros, garantindo assim os direitos e garantias de qualquer cidadão, bem como todo tipo de trabalho que coloquem em risco a vida de qualquer pessoa, dispondo do direito de denunciar as autoridades qualquer tipo de situação que promova a utilização de violência física, psicológica ou outra.
        </p>
        <div class="row mx-0">
          <ButtonScrollContato name="Fale com um especialista" variation="lg-azul" />
        </div>
      </div>
    </div>
  </section>
</template>
<script>
import ButtonScrollContato from '~/components/buttons/button-scroll-contato.vue'
import HeaderSections from '~/components/parts/HeaderSections.vue'

export default {
  components: { HeaderSections, ButtonScrollContato },
  layout: 'layoutSobre',
  head: {
    link: [
      { rel: 'alternate', href: 'https://universaldetetives.com.br/sobre', hreflang: 'x-default' },
      { rel: 'alternate', href: 'https://universaldetetives.com.br/sobre', hreflang: 'pt-br' },
      { rel: 'alternate', href: 'https://universaldetectives.pt/sobre', hreflang: 'pt' }
    ]
  }
}
</script>
<style lang="scss" scoped>

</style>
