<template>
  <UHeader>
    <template #left>
      <div class="flex items-center space-x-3">
        <img src="/images/logo.svg" alt="Kobako Logo" class="h-8 w-auto" />

        <h1 class="text-xl font-bold text-gray-900 dark:text-white">
          Kobako
        </h1>
      </div>
    </template>

    <template #right>
      <UButton label="Download App" variant="subtle" class="hidden lg:block" />

      <UColorModeButton />
    </template>
  </UHeader>
</template>
