<template>
  <div id="app">
    <router-view />
    <h1>黑马头条</h1>
    <div>
      <i class="iconfont icon-dianzan2"></i>
    </div>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="info">信息按钮</van-button>
    <van-button type="default">默认按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
    <van-cell-group inset>
      <van-cell title="单元格" value="内容" />
      <van-cell title="单元格" value="内容" label="描述信息" />
    </van-cell-group>
    <van-icon name="chat-o" />
    <van-icon name="https://b.yzcdn.cn/vant/icon-demo-1126.png" />
    <div class="box"></div>
  </div>
</template>
<script>
export default {}
</script>

<style lang="less">
.box {
  width: 300px;
  height: 288px;
  background-color: pink;
}
</style>
