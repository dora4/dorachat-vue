<script setup>
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
      <ToolingIcon />
    </template>
    <template #heading>Dora Box</template>
    <h6>
    <p>https://doracrypto.com</p>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Dora Chat</template>

    <h6>
Dora Chat is a social app that supports friend chat and group chat. If you have friends, you are never alone. Welcome to join the Dora Chat community.
    <a href="https://www.pgyer.com/dorachat/" target="_blank">Details</a>
    </h6>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>

      <SupportIcon />
    </template>
    <template #heading>Contact Us</template>

     <p>
    <a href="https://www.youtube.com/channel/UCEDRPkqMGeBN3UiqLC6Qj-g">Youtube</a>
     </p>
     <p>
         <a href="https://discord.com/channels/1234248413701476352/1234248413701476354">Discord</a>
     </p>
     <p>
    <a href="https://github.com/dora4">Github</a>
     </p>

  </WelcomeItem>
</template>
