<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'

const openReadmeInEditor = () => fetch('/__open-in-editor?file=README.md')
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>책좀읽자</template>

    ㄱㅁㄷ ㅇㅈ?
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>가방도 좀 사고!</template>

    ㅉㄺ는 가방에 넣어도 눈이 아프다 ㄱㅁㄷㅇㅈ?? 대체 뭐가 문제인
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>육각형</template>

    메이플하면 진정한 육각형의 사나이 ㄱㅁㄷㅇㅈ?
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>대임이다 진짜</template>

    ㅉㄹㄱ하자 제발!
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>쪼롤은 사랑이다</template>

    As an independent project, Vue relies on community backing for its sustainability. You can help
    us by
    <a href="https://www.naver.com/" target="_blank" rel="noopener">becoming a sponsor</a>.
  </WelcomeItem>
</template>
