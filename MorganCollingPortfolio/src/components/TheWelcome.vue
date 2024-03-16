<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import LinkedInIcon from './icons/IconLinkedIn.vue'
import GitHubIcon from './icons/IconGitHub.vue'
import Print3DIcon from './icons/Icon3D.vue'
import EtsyIcon from './icons/IconEtsy.vue'
import MediumIcon from './icons/IconMedium.vue'
import ItchIcon from './icons/IconItch.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <GitHubIcon />
    </template>
    <template #heading>GitHub Repositories</template>

    You can find my latest public repositories on my
    <a href="https://github.com/MorganAaronColling" target="_blank" rel="noopener">Github page</a>. My self driving car and plant disease detection projects can be found there.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <MediumIcon />
    </template>
    <template #heading>Medium Articles</template>

    This is my
    <a href="https://medium.com/@morganaaroncolling" target="_blank" rel="noopener">Medium page</a>, where I write about technical things that you might find useful!
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ItchIcon />
    </template>
    <template #heading>Game Development</template>

    This is my
    <a href="https://baphomet2k.itch.io/" target="_blank" rel="noopener">Itch.io page</a>. I upload my game demos here.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <LinkedInIcon />
    </template>
    <template #heading>LinkedIn</template>

    My
    <a href="https://www.linkedin.com/in/morganaaroncolling/" target="_blank" rel="noopener">LinkedIn Page</a>
    provides you with all information about my career so far.
  </WelcomeItem>

  <!-- <WelcomeItem>
    <template #icon>
      <Print3DIcon />
    </template>
    <template #heading>3D Printing</template>

    Check out my
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener">3D Models</a> I have designed.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EtsyIcon />
    </template>
    <template #heading>Etsy</template>

    My 
    <a href="https://baphometindustries.etsy.com" target="_blank" rel="noopener">Etsy shop</a> contains all my 3D printed products.

  </WelcomeItem> -->

</template>
