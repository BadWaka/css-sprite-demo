# css-sprite-demo
CSS Sprite 雪碧图学习Demo

> 参考视频地址：[CSS Sprite雪碧图应用-慕课网](http://www.imooc.com/learn/93)

> GitHub：https://github.com/BadWaka/css-sprite-demo

# 适用场景

1. 静态图片，不随用户信息的变化而变化
2. 小图片，图片容量比较小
3. 加载量比较大

一些大图不建议拼成雪碧图

![](http://upload-images.jianshu.io/upload_images/1828354-c35c239bae7c3f5a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

# 实现原理

通过CSS属性 `background-position`，控制展示区域的大小

```
background-position: 0 -24px;
```

# 效果

![](http://upload-images.jianshu.io/upload_images/1828354-2d4266294dc7dba7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)