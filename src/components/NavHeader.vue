<template>
    <div>
        <!-- 头部导航栏 -->
        <div id="header">
            <div class="hide" ref="show"></div>
            <!-- 中间列表链接 -->
            <div class="list">
                <!-- logo和地图区域 -->
                <div class="logo">
                    <!-- <img src="../assets/home/logo.png" alt=""> -->
                    <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;厦门</span>
                    <span class="el-icon-arrow-down"></span>
                </div>
                <!-- 列表链接 -->
                <ul>
                    <!-- <img src="../assets/home/one.png" alt=""> -->
                    <li>
                        <a href="index.html">首页</a>
                    </li>
                    <li>
                        <a href="buy.html">买车</a>
                    </li>
                    <li>
                        <a href="sell.html">卖车</a>
                    </li>
                    <li>
                        <a href="newcar.html">新车</a>
                    </li>
                    <li>
                        <a href="theme.html">精品主题
                            <!-- <span class="el-icon-caret-bottom"></span> -->
                        </a>
                    </li>
                    <li>
                        <a href="join.html">招商加盟
                            <!-- <span class="el-icon-caret-bottom"></span> -->
                        </a>
                    </li>
                    <li>
                        <a href="find.html">门店查找</a>
                    </li>
                    <li>400-068-5858</li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {};
</script>

<style>
/* // 头部样式 */
#header {
  width: 100%;
  height: 60px;
  /* // background: white; */
  position: fixed;
  top: 0;
  left: 0;
  color: #000;
  font-size: 13px;
  z-index: 111;

  
}
  .hide {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 60px;
    background: white;
    border: 1px solid #ccc;
    /* // display: none; */
  }
  .list {
    position: absolute;
    top: 0;
    left: 50%;
    margin-left: -600px;
    width: 1200px;
    height: 100%;
    /* // background: white; */
    
    
  }
  ul {
      width: 640px;
      height: 100%;
      /* // background: yellow; */
      float: right;
      line-height: 60px;
      
      
    }
  li {
        float: left;
        margin-left: 19px;
        cursor: pointer;
      }
      li:hover {
        color: red;
      }
      li:first-child {
        margin-left: 0;
      }
      li:last-child {
        font-size: 26px;
        color: red;
        font-weight: bold;
      }
      img {
        position: absolute;
        top: 6px;
        left: 722px;
      }
  .logo {
      float: left;
      width: 300px;
      height: 100%;
      /* // background: red; */
      line-height: 60px;
      
    }
    img {
        vertical-align: middle;
      }
</style>
