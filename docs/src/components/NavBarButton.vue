<template>
  <button class="nav-bar-button inline-flex text-xl mx-1.5 p-2">
    <slot/>
  </button>
</template>

<style lang="postcss" scoped>
.nav-bar-button {
  @apply rounded-lg
    text-current text-1.05rem cursor-pointer
    focus:outline-none focus:bg-warm-gray-200
    bg-warm-gray-100 hover:bg-warm-gray-200
    dark:(bg-dark-400 hover:bg-dark-300 focus:bg-dark-300) overflow-hidden;
}
</style>
