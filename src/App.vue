<template>
  <h1 class="hidden">Your CSS is disabled!</h1>
  <img
    id="siteBackground"
    src="@/visuals/PageBackground.svg"
    alt="Background" aria-hidden="true"
  />
  <RouterView />
</template>

<style scoped lang="sass">
  #siteBackground
    position: fixed
    top: 50%
    left: 50%
    transform: translate(-50%, -50%)

    min-width: 100%
    min-height: 100%
    z-index: 0
    pointer-events: none
    opacity: 0.2
</style>
