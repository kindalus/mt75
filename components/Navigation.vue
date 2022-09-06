<template>
  <div class="relative">
    <div class="absolute navigation flex gap-2 justify-center">
      <div class="grow-0 px-8 py-4 m-4 bg-black bg-opacity-10 rounded-full">
        <img class="h-10" src="/images/logo.png" alt="" />
      </div>
      <div class="grow" />
      <div>
        <span class="navigation-link">Link 1</span>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
//.navigation {}

.navigation-link {
  @apply text-sm;
}
</style>
