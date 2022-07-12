<template>
  <div class="tabBar">
    <div class="homePage">
      <img class="img" src="../../assets/images/首页默认.svg" alt="">
      <div class="tagging">首页</div>
    </div>
    <div class="product">
      <img class="img" src="../../assets/images/产品默认.svg" alt="">
      <div class="tagging">产品</div>
    </div>
    <div class="news">
      <img class="img" src="../../assets/images/消息默认.svg" alt="">
      <div class="tagging">消息</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "tabBar",
  data() {
    return {};
  },
};
</script>

<style scoped>
.tabBar {
  border-top: 1px solid #F2F3F5;
  height: 49px;
  display: flex;
  justify-content: space-around;
}
.img {
  width: 20px;
  height: 20px;
  margin-top: 7px;
}
.tagging {
  transform: translateX(-2px);
  font-size: 12px;
}
</style>