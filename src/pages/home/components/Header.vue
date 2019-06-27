<template>
  <div class="header">
    <div class="header-left">
      <span class="iconfont back-icon">&#xe84f;</span>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe82e;</span>
      输入城市/景点/游玩主题
    </div>
    <div class="header-right">
      城市
      <span class="iconfont down-icon">&#xe843;</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
@import '~styles/varibles.styl'
.header
  display flex
  line-height 0.86rem
  background-color $bgColor
  color #fff
  .header-left
    width 0.64rem
    float left
    .back-icon
      margin-left 0.1rem
      text-align center
      font-size 0.4rem
  .header-input
    flex 1
    height 0.64rem
    line-height 0.64rem
    margin-top 0.12rem
    margin-left 0.2rem
    padding-left 0.2rem
    background #fff
    border-radius 0.1rem
    color #ccc
  .header-right
    width 1.24rem
    float right
    text-align center
    .down-icon
      margin-left -0.04rem
      font-size 0.24rem
</style>

