<template>
    <div id="app">
        <div class="search-background">
            <img class="search-icon" src="https://css.gomein.net.cn/plus/style/index/images/grass_logo.png?v=2017092001" alt="">
            <div class="search">
                <van-icon class="icon-search" name="search" size="1.3rem"/>
                <h1>香肠派对</h1>
            </div>
            <div class="register"></div>
        </div>
    </div>
</template>


<script>


export default {
    
}
</script>

<style>
.search-background{
    width: 100%;
    height: 3.3rem;
    background-color: red;
    display: flex;
    justify-content:space-around;
}
.search-icon{
    width: 1.8rem;
    height: 1.8rem;
    float: left;
    margin-top: 0.7rem;
}
.search{
    width:12.8rem;
    height: 2.3rem;
    background-color: #f0f0f0;
    border-radius: 2rem; 
    margin-top: 0.5rem;
}
.icon-search{
    float: left;
    margin-top: 0.5rem;
    margin-left: 0.5rem;
    color: #999;
}
.search h1{
    color: #999;
    line-height: 1rem;
    font-size: 0.9rem;
    float: left;
    margin-left: 0.5rem;
}
.register{
    width: 4.5rem;
    height: 3.3rem;
    background-color: pink;
}
</style>

