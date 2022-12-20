<script setup>
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconComponentes.vue";
import ToolingIcon from "./icons/IconMovil.vue";
import EcosystemIcon from "./icons/IconPeriféricos.vue";
import CommunityIcon from "./icons/IconSilla.vue";
import SupportIcon from "./icons/IconVisitanos.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Componentes</template>
    Componentes y todo relacionado con procesadores
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Smartphones</template>

    Ofrecemos un amplio catálogo de smartphones de diversas marcas

    <br />

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Periféricos</template>

    En nuestra tienda podras encontrar todo tipo de periféricos
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Sillas</template>

    Encuentra el mejor confort con nuestras sillas de marcas como "SECRETLAB"
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Visitanos</template>

    Ven a visitarnos a nuestra páguina web
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener"
      >Diatech.com</a
    >.
  </WelcomeItem>
</template>
