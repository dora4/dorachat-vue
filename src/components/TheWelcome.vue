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
      <CommunityIcon />
    </template>
    <template #heading>Dora Chat</template>

    A Web3 social platform. Welcome to join the Dora Chat community.
    <a href="https://www.pgyer.com/dorachat/" target="_blank">Details</a>
  </WelcomeItem>


      <WelcomeItem>
        <template #icon>
          <ToolingIcon />
        </template>
        <template #heading>Encryption and decryption tools for private information</template>

        <p>
            <a href="https://dorachat.oss-cn-hongkong.aliyuncs.com/app-dora-release.apk">To my future self</a>
        </p>

      </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Contact Us</template>
     <p>
         <a href="https://discord.com/channels/1234248413701476352/1234248413701476354">Discord</a>
     </p>
     <p>
    <a href="https://github.com/dora4">Github</a>
     </p>
     <p>
    <a href="https://juejin.cn/user/2656895088205453">Juejin</a>
     </p>
     <p>
    <a href="https://blog.csdn.net/a_lwh____?spm=1011.2480.3001.5343">CSDN</a>
     </p>
     <p>
    <a href="https://www.tiktok.com/@dorachat.com">Tiktok</a>
     </p>
     <p>
    <a href="https://www.youtube.com/@dorachat01">Youtube</a>
     </p>
  </WelcomeItem>
</template>
