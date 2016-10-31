# carousel
原生JavaScript 图片轮播

图片的淡入淡出效果

使用方法：

在html中添加以下代码到对应位置

```html
<!--banner start-->
<div id="banner">
    <ul class="banner-list">
        <li class="bannerOn">
            <a href=""><img src="img/banner1.jpg" alt='banner1'></a>
        </li>
        <li>
            <a href=""><img src="img/banner2.jpg" alt='banner2'></a>
        </li>
        <li>
            <a href=""><img src="img/banner3.jpg" alt='banner3'></a>
        </li>
    </ul>

    <ul id="indexList">
        <li class="indexOn"></li>
        <li></li>
        <li></li>
    </ul>

</div>
<!--banner-->
```

引入css文件和js文件

```html
<!--引入CSS样式-->
<link rel="stylesheet" href="css/style.css">
<!---->
```

```html
<!--引入JS文件-->
<script src="js/carousel.js"></script>
<!---->
```

效果图： ![效果图](https://github.com/chuyun/carousel/blob/master/img/xiaoguo.png)
