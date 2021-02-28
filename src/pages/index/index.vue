<template>
  <view class="content">
    <!-- text==span  view==div -->
    <view> <text class="title">1111</text><text class="title">222</text> </view>
  </view>
</template>

<script>
export default {
  data() {
    return {};
  },
  onLoad() {},
  methods: {},
};
</script>

<style lang="scss">
/* page==body */
page {
  /* background: pink; */
}
/* 单位 px rox rem vh vw */
.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  .title {
    font-size: 36rpx;
    color: #8f8f94;
  }
}


</style>
