# LoveRecord
Love Record 一个照片轮播的动画网站，纪录了我们在一起的时间。轮播背景用我、她、我们的照片运用上素描大师的滤镜营造故事效果，并且每张图片配上那么一两句话，描述时间地点等信息。

[点此，查看我们的记忆](https://iamjohnnyzhuang.github.io/LoveRecord/iloveu.html) 
[生日快乐](https://htmlpreview.github.io/?https://github.com/ziyezhang/happybirthday/blob/master/iloveu.html)



**兼容性**

目前已测试：

Chrome/Firefox/Edge/Ie 11



##此项目已迁移至[eternity](https://github.com/iamjohnnyzhuang/eternity)
由于之前托管在github pages上，因此只能存放纯静态文件，导致不得不将很多图片地址以及文字硬编码在代码中，非常不利于长久的维护。因此在自己的VPS搭建了Node JS服务器。为什么用Node Js呢，因为足够轻量， Node Js + Express框架非常轻量的搭建了我的项目，连数据库都没有单纯的读写文件，够轻量吧？

借助Node Js服务器，改善了代码的冗余度，方便后期开发维护。 同时增加了管理员页面(需要账号密码哦): 
这样，可以在图形界面上轻松的上传新的图片以及文字了~
