<script setup lang="ts">
import { VPTeamMembers } from 'vitepress/theme'
defineOptions({
  name:'HomePage'
})
const members = [
  {
    avatar: 'https://www.github.com/daguanren21.png',
    name: 'daguanren Bob',
    title: 'Author',
    links: [
      { icon: 'github', link: 'https://github.com/daguanren21' },
    ],
  },
]
</script>
<template>
  <div flex="~ col wrap" items-center mt8>
    <VPTeamMembers size="small" :members="members" />
  </div>
</template>
<style scoped>
</style>
