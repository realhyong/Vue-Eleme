<template lang="html">
  <span class="iconMap" :class="iconClassMap[iconType]"></span>
</template>

<script>
export default {
  props: {
    iconType: Number
  },
  created() {
    this.iconClassMap = ['none', 'hot', 'new']
  }
}

</script>

<style lang="stylus" scoped>
@import '../../common/stylus/mixin'
  .iconMap
    display inline-block
    background-size 100% 100%
    background-repeat no-repeat
    width 15px
    height 15px
    &.hot
      bg-image('hot_2')
    &.new
      bg-image('new_2')
</style>
