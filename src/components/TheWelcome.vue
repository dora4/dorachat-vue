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
    <template #heading>隐私保险箱</template>
    <h6>
    隐私是每个人都应该得到尊重和保护的基本权利。但是，随着社交媒体和数字通信的普及，

    我们的个人隐私越来越容易受到侵犯。因此，我们需要一种可以帮助我们保护个人隐私的

    工具，而这个工具就是【隐私保险箱】。【隐私保险箱】是一款特殊的应用程序，它可以

    让您将敏感或私人内容锁定起来。通过使用【隐私保险箱】，您可以保护这些内容不被任

    何人偷窥、窃取或滥用，甚至是您自己。【隐私保险箱】的最大特点是，您可以将这些内

    容锁定起来并设定一个特定的日期和时间，在此之前，这些内容无法被解锁。这意味着，

    如果您有任何敏感内容需要妥善保护，您可以使用【隐私保险箱】将其保护起来，并设置

    未来的日期和时间，这样，即使您失去了手机，隐私数据也不会丢失。总之，如果您在保

    护个人隐私方面非常注重，那么【隐私保险箱】是一款您绝不能错过的应用程序，您可以

    通过它将隐私内容拆分后分散保存以保护您的隐私。
    <a href="https://www.pgyer.com/privacybox/" target="_blank">下载安装</a>
    </h6>
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Dora Chat</template>

    <h6>
    Dora Chat是一款社交类app，支持好友聊天和群聊，有朋友，不孤单，欢迎加入Dora Chat社区。
    <a href="https://www.pgyer.com/dorachat/" target="_blank">下载安装</a>
    </h6>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>感谢您的支持</template>

    <h4>
    如果有任何建议或疑问请联系Dora Chat官方唯一客服ID：dorachat。
    </h4>
  </WelcomeItem>
</template>
