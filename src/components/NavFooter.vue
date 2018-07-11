<template>
    <div>
        <!-- 底部列表页 -->
        <div class="footer">
            <div class="conter">
                <div class="top">
                    <ul>
                        <li>关于米车网</li>
                        <li>二手车导购</li>
                        <li>二手车交易指南</li>
                    </ul>
                    <!-- <div class="img"><img src="../assets/home/QR.png" alt=""></div> -->
                </div>
                <div class="middle">
                    <ul>
                        <li>
                            热门城市:
                            <a href=" ">厦门二手车</a>
                            <a href="javascript:;">厦门二手车</a>
                            <a href="javascript:;">厦门二手车</a>
                            <a href="javascript:;">厦门二手车</a>
                            <a href="javascript:;">厦门二手车</a>
                            <a href="javascript:;">厦门二手车</a>
                            <a href="javascript:;">厦门二手车</a>
                        </li>
                        <li>
                            热门品牌:
                            <a href="javascript:;">厦门二手车</a>
                            <a href="javascript:;">厦门二手车</a>
                            <a href="javascript:;">厦门二手车</a>
                            <a href="javascript:;">厦门二手车</a>
                            <a href="javascript:;">厦门二手车</a>
                            <a href="javascript:;">厦门二手车</a>
                            <a href="javascript:;">厦门二手车</a>
                            <a href="javascript:;">厦门二手车</a>
                        </li>
                        <li>
                            热门车系:
                            <a href="javascript:;">厦门二手车</a>
                            <a href="javascript:;">厦门二手车</a>
                            <a href="javascript:;">厦门二手车</a>
                            <a href="javascript:;">厦门二手车</a>
                            <a href="javascript:;">厦门二手车</a>
                            <a href="javascript:;">厦门二手车</a>
                            <a href="javascript:;">厦门二手车</a>
                            <a href="javascript:;">厦门二手车</a>
                        </li>
                    </ul>
                </div>
                <div class="fall">
                    <span>版权所有 @ www.micw.com [闽ICP备14008741-1号]</span>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {};
</script>

<style>
/* 底部区域 */
.footer {
  width: 100%;
  height: 300px;
  min-width: 1200px;
  background: #eee;
  position: relative;
}
/* 中间内容区 */
.conter {
  margin: 0 auto;
  /* margin-left: -357px; */
  width: 1200px;
  height: 100%;
}
.top {
  width: 100%;
  height: 106px;
}

.top ul {
  width: 600px;
  height: 100%;
  float: left;
}
.top li {
  font-size: 24px;
  float: left;
  line-height: 106px;
}
.top li ~ li {
  margin-left: 40px;
}
.top .img {
  width: 500px;
  height: 100%;
  float: right;
  line-height: 10rem;
}

.middle {
  width: 100%;
  height: 160px;
  font-size: 15px;
}
.middle li {
  height: 40px;
  color: #8a8a8a;
  line-height: 36px;
  margin-top: 10px;
}
.middle a {
  margin: 0 10px 0 10px;
  color: #000;
}
.fall {
  width: 100%;
  height: 20px;
  text-align: center;
  font-size: 13px;
}
</style>


