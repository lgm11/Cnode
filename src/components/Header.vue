<template>
    <div class="header">
        <img src="https://static2.cnodejs.org/public/images/cnodejs_light.svg" alt="">
        <ul>
            <li><a href="">首页</a></li>
            <li><a href="">新手入门</a></li>
            <li><a href="">API</a></li>
            <li><a href="">关于</a></li>
            <li><a href="">注册</a></li>
            <li><a href="">登录</a></li>
        </ul>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
.header{
    background: #5a5555;
    height: 50px;
}
ul{
    list-style: none;
    float: right;
    margin: 4px;
}
li{
    display: inline-block;
    padding: 10px 15px;
}
img{
    max-width: 120px;
    margin-left: 50px;
    margin-top: 10px;
}
a{
    text-decoration: none;
    color: #ccc;
    font-size: 14px;
    text-shadow: none;
}
</style>