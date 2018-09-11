<template>
    <div class="login">
        <header class="header">12346</header>
        <div class="login-main">
            <div class="login-box">
                <div class="login-title">核销端</div>
                <div class="login-control">
                    <div class="user-id">
                        <span class="icon">icon</span>
                        <input type="text">
                    </div>
                    <div class="user-pw">
                        <span class="icon">icon</span>
                        <input type="password">
                    </div>
                    <div class="login-btn">
                        <button>登录</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="less" scoped>
.login {
    width: 100%;
    height: 100%;
    display:flex;
    flex-direction: column;
    .header {
        height:170px;
        background:orange;
    }
    .login-main {
        flex-grow: 1;
        background: rgb(226, 226, 226);
        position: relative;
        .login-box {
            position: absolute;
            width: 65%;
            left: 50%;
            top:10%;
            transform: translateX(-50%);
            background:green;
            .login-title {
                margin:0 auto;
                font-size: 20px;
                height: 30px;
                line-height: 30px;
                text-align: center;
                width: 100px;
                border-top-left-radius: 15px;
                border-top-right-radius: 15px;
                background:#fff;
            }
            .login-control {
                background:#fff;
                border-radius: 30px;
                width: 100%;
                .user-id,.user-pw {
                    height: 30px; 
                    // background:red;
                    width:80%;
                    margin:0 auto;
                    // text-align: center;
                    .icon {
                        position: absolute;
                        line-height: 25px;
                    }
                    input {
                        margin-top: 5px;
                        height: 25px;
                        width: 100%;
                        border:0;
                        border-bottom: 1px solid #ccc;
                        // text-indent:3em;
                    }
                }
                .login-btn {
                    margin: 5px;
                    height: 50px;
                    text-align: center; 
                    line-height: 50px;
                }
            }
        }
    }
}
</style>
