<template>
    <div class="sign-up">
        <header>请填写资料</header>
        <div class="signup-msg">
            <ul>
                <li>
                    <div class="title">
                        <span class="icon"></span>  
                        <span class="desc">姓氏</span>
                    </div>
                    <div class="cont">
                        <input type="text" placeholder="请输入您的姓氏">
                    </div>
                </li>
                <li>
                    <div class="title">
                        <span class="icon"></span>
                        <span class="desc">性别</span>
                    </div>
                    <div class="cont">
                        <form >
                            <input type="radio" value="male">
                            <label for="">男生</label>
                            <input type="radio" value="female">
                            <label for="">女生</label>
                        </form>
                    </div>
                </li>
                <li>
                    <div class="title">
                        <span class="icon"></span>
                        <span class="desc">联系电话</span>
                    </div>
                    <div class="cont">
                        <input type="text" placeholder="请输入您的姓氏">
                    </div>
                </li>
                <li>
                    <div class="title">
                        <span class="icon"></span>
                        <span class="desc">居住地区</span>
                    </div>
                    <div class="cont">
                        <input type="text" placeholder="请选择您的居住地区">
                    </div>
                </li>
                <li>
                    <div class="title">
                        <span class="icon"></span>
                        <span class="desc">注册门店</span>
                    </div>
                    <div class="cont">
                        <input type="text" placeholder="请选择您的注册门店">
                    </div>
                </li>
            </ul>
        </div>
        <div class="btn">
            <button>成为会员</button>
        </div>
    </div>
</template>
<style lang="less" scoped>
.sign-up {
    height: 100%;
    header {
        background:orange;
        height: 50px;
        text-align: center;
        line-height: 50px;
        color:#fff;
    }
    .signup-msg {
        ul {
            li {
                height: 40px;
                border:1px solid red;
                display: flex;
                .title,.cont {
                    height: 100%;
                    line-height: 40px;
                }
                .title {
                    width: 70px;
                }
                .cont {
                    flex: 1;
                }

            }
        }
    }
    .btn {
        height: 50px;
        border:1px solid red;
        margin-top: 20px;
        button {
            margin-left:15%;
            border:1px solid red;
            background:transparent;
            width: 70%;
            height: 100%;
            text-align: center;
            border-radius: 15px;
        }
    }
}
</style>

