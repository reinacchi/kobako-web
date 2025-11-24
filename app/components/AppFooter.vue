<template>
  <USeparator
    class="h-px"
  />

  <UFooter :ui="{ top: 'border-b border-default' }">
    <template #left>
      <p class="text-sm text-muted">
        Copyright © {{ new Date().getFullYear() }} <span class="text-primary">2rkf</span>. All rights reserved.
      </p>
    </template>

    <template #right>
      <UButton
        to="https://discord.gg/fmxR8hUPSw"
        target="_blank"
        icon="i-simple-icons-discord"
        color="neutral"
        variant="ghost"
      />
      <UButton
        to="https://twitter.com/reinacchi_"
        target="_blank"
        icon="i-simple-icons-twitter"
        color="neutral"
        variant="ghost"
      />
      <UButton
        to="https://github.com/reinacchi/kobako-web"
        target="_blank"
        icon="i-simple-icons-github"
        color="neutral"
        variant="ghost"
      />
    </template>
  </UFooter>
</template>