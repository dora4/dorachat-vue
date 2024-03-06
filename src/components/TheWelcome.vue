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
Privacy is a basic right that everyone should be respected and protected. However, with the popularity of social media and digital communications,

     Our personal privacy is increasingly vulnerable to invasion. Therefore, we need a method that can help us protect personal privacy

     tool, and this tool is [Privacy Safe]. [Privacy Safe] is a special application that can

     Lets you lock away sensitive or private content. By using [Privacy Vault], you can protect this content from any

     Who snoops, steals or misuses it, even yourself. The biggest feature of [Privacy Safe] is that you can store the contents

     Once the content is locked and set to a specific date and time, the content cannot be unlocked until then. this means,

     If you have any sensitive content that needs to be properly protected, you can use [Privacy Vault] to protect it and set

     Future date and time so that even if you lose your phone, your private data will not be lost. In summary, if you are insuring

     If you attach great importance to protecting personal privacy, then [Privacy Safe] is an application you must not miss. You can

     It splits private content and saves it in scattered ways to protect your privacy.
    <a href="https://www.pgyer.com/dorabox/" target="_blank">Download APK</a>
    </h6>
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Dora Chat</template>

    <h6>
Dora Chat is a social app that supports friend chat and group chat. If you have friends, you are never alone. Welcome to join the Dora Chat community.
    <a href="https://www.pgyer.com/dorachat/" target="_blank">Download APK</a>
    </h6>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Thank you for watching</template>
     dora924666990@gmail.com
  </WelcomeItem>
</template>
