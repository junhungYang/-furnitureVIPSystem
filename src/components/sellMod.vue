<template>
    <div class="sellMod">
        <header class="shop-name">沙拉沙漠(GDFS)</header>
        <div class="content">
            <div class="data-wrap">
                <div class="title">会员资料</div>
                <ul class="user-data">
                    <li>
                        <span>会员名称</span>
                        <span>唐先生</span>
                    </li>
                    <li>
                        <span>会员编号</span>
                        <span>C00001</span>
                    </li>
                    <li>
                        <span>所属门店</span>
                        <span>GDFS</span>
                    </li>
                    <li>
                        <span>购买系列</span>
                        <span>听风细雨</span>
                    </li>
                </ul>
                <div class="sell-control">
                    <div class="cancel">取消</div>
                    <div class="line"></div>
                    <div class="confirm">核销</div>
                </div>
            </div>
            <div class="control">
                <div class="scanCode">点击扫码</div>
                <div class="check-history">查看核销记录</div>
            </div>
        </div>
    </div>
</template>
<style lang="less" scoped>
.sellMod {
  height: 100%;
  display: flex;
  flex-direction: column;
  .shop-name {
    height: 30px;
    border: 1px solid red;
    text-align: center;
    line-height: 30px;
  }
  .content {
    flex: 1;
    .data-wrap {
      margin: 0 auto;
      margin-top: 70px;
      width: 70%;
      border: 1px solid red;
      .title {
        height: 30px;
        border: 1px solid green;
        text-align: center;
      }
      .user-data {
        li {
          height: 30px;
          border: 1px solid orange;
        }
      }
      .sell-control {
        height: 50px;
        display: flex;
        .cancel,
        .confirm {
          flex: 1;
          text-align: center;
          line-height: 50px;
        }
        .line {
          height: 30px;
          width: 1px;
          background: #ccc;
        }
      }
    }
  }
  .control {
    margin-top: 50px;
    .scanCode,
    .check-history {
      width: 150px;
      height: 50px;
      line-height: 50px;
      text-align: center;
      margin: 0 auto;
      border: 1px solid red;
      border-radius: 10px;
    }
    .check-history {
      margin-top: 30px;
    }
  }
}
</style>

