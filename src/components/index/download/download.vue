<template>
    <div id="app">
        <div class="download-background">
            <div class="left">
                <div class="delete">
                <van-icon name="cross" size="1.5rem"/>
                </div>
                <img class="download-icon" src="https://gfs9.gomein.net.cn/T1VnKvB7_T1RCvBVdK.png">
                <div class="text">
                    <div class="text-a">注册享好礼</div>
                    <div class="text-b">送310元礼包</div>
                </div>
            </div>
            <div class="right">
                <a href="#javescript">下载领取</a>
            </div>
        </div>
    </div>
</template>

<script>

export default {
  name: 'app',
  components: {
    
  }
}
</script>

<style>
.download-background{
    width: 100%;
    height: 4rem;
    background-color: #333;
}
.left{
    float:left;
}
.delete{
    color: #fff;
    margin:1.1rem 0.8rem;
    float: left;
}
.download-icon{
    width:3rem;
    height: 3rem;
    float: left;
    margin-top: 0.5rem;
}
.text{
    width: 10rem;
    margin-left: 0.5rem;
    float: left;
}
.text .text-a{
    font-size: 0.9rem;
    margin-top: 0.5rem;
    color: #fff;
    float: left;
    line-height: 1.8rem;
    overflow: hidden;
    white-space: nowrap;
    width: 10rem;
}
.text .text-b{
    font-size: 0.8rem;
    float: left;
    line-height: 1rem;
    overflow: hidden;
    white-space: nowrap;
    color: #999;
    width: 10rem;
}
.right{
    width: 6rem;
    height: 4rem;
    background-color:rgb(172, 54, 172);
    float: right;
    text-align: center;
}
.right a{
    font-size: 1rem;
    line-height: 4rem;
    color:#fff;
}
</style>
