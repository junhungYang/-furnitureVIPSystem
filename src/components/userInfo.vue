<template>
    <div class="userInfo">
        <header>
            <img src="" alt="">
        </header>
        <div class="my-msg">
            <div class="msg-wrap">
                <div class="desc">
                    <ul>
                        <li v-for="item in 4">
                            <span>会员名称</span>
                            <span>唐先生</span>
                        </li>
                    </ul>
                    <div class="footer">点击修改个人资料</div>
                </div>
                <div class="QR-code"></div>
            </div>
            <div class="footer">出示上面二维码于电源可进行下单</div>
        </div>
        <div class="signle-record">
            <div class="title">下单记录</div>
            <ul>
                <li v-for="item in 6">
                    <div class="shop-time">
                        <div class="shop">
                            所选门店: <span>GDFS</span>
                        </div>
                        <div class="when">
                            <span class="date">2018-07-11</span>
                            <span class="time">13:25:04</span>
                        </div>
                    </div>
                    <div class="series">
                        购买系列: <span>听风细雨</span>
                    </div>
                </li>
            </ul>
        </div>
    </div>
</template>
<style lang="less" scoped>
.userInfo {
  display: flex;
  flex-direction: column;
  header {
    height: 150px;
    border: 1px solid red;
  }
  .my-msg {
    border: 1px solid red;
    border-bottom-left-radius: 15px;
    border-bottom-right-radius: 15px;
    margin-bottom: 10px;
    .msg-wrap {
      height: 220px;
      display: flex;
      .desc {
        flex: 1;
        .footer {
          text-align: center;
        }
      }
      .QR-code {
        width: 220px;
        height: 220px;
        border: 1px solid green;
      }
    }
    .footer {
      height: 30px;
    }
  }
  .signle-record {
    flex: 1;
    overflow: hidden;
    .title {
      height: 30px;
      border: 1px solid orange;
    }
    ul {
      li {
        height: 50px;
        border: 1px solid #ccc;
        display: flex;
        .shop-time {
            flex:1;
            
        }
        .series {
            width: 150px;
        }
      }
    }
  }
}
</style>

