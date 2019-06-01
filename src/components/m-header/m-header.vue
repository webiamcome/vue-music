<template>
  <!-- ![recommend interface](https://i.loli.net/2019/04/06/5ca861da160ba.png) -->
  <div class="m-header">
    <div class="icon"></div>
    <h1 class="text">Chicken Music</h1>
  </div>
</template>
<style lang="stylus" scoped>
  @import '~common/stylus/variable';
  @import '~common/stylus/mixin';

  .m-header
    position: relative;
    height: 44px;
    text-align: center;
    font-size: 0;
    color: $color-theme;
    .icon
      display: inline-block;
      margin-top: 6px;
      margin-right: 9px;
      width: 30px;
      height: 32px;
      vertical-align: top;
      bg-image('logo');
      background-size: 30px 32px;
    .text
      display: inline-block;
      line-height: 44px;
      vertical-align: top;
      font-size: $font-size-large;
    .mine
      position: absolute;
      top: 0;
      right: 0;
      .icon-mine
        display: block;
        padding: 12px;
        font-size: 20px;
        color: $color-theme;
</style>
