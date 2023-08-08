<template>
  <div>
    <slot></slot>
  </div>
</template>

<style scoped>
  .label {
    fill: white;
  }
  .bottle, .wine-text {
    fill: black;
  }
  .flor {
    fill: #ccc;
  }
  .bkimg {
    filter:url(#inverse)
  }
</style>