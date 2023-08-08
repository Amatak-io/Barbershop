<template>
  <div class="">
    <slot>This is Black Page</slot>
  </div>
</template>

<style scoped>
  .label {
    fill: black;
  }
  .bottle, .wine-text {
    fill: white;
  }
  .flor {
    fill: #ccc;
  }
  .bkimg {
    filter:url(#inverse)
  }
</style>