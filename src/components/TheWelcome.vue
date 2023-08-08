<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Regular</template>

    $20
    <a href="#" target="_blank" rel="noopener">Book Now</a>.
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Regular Fade</template>

    $25
    <a href="#" target="_blank" rel="noopener">Book Now</a>.
  </WelcomeItem><WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Fade(Taper-Zero-Skin</template>

    $27-$30
    <a href="#" target="_blank" rel="noopener">Book Now</a>.
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Beard (Line-Trim-Fade</template>

    $10-$20
    <a href="#" target="_blank" rel="noopener">Book Now</a>.
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Hair Wash</template>

    $10
    <a href="#" target="_blank" rel="noopener">Book Now</a>.
  </WelcomeItem>

</template>
