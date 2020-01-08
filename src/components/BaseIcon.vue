<template>
<div class="icon-wrapper">
  <svg class="icon" :width="width" :height="height">
    <use v-bind="{ 'xlink:href':'/spotify.svg'}"></use>
  </svg>
  <slot></slot>
</div>
</template>

<script>
  export default {
    props: {
      name: String,
      width: { 
        type: [Number, String],
        default: 24
      },
      height: { 
        type: [Number, String],
        default: 24
      }
    }
  }
</script>

<style lang="sass" scoped>
  
</style>
