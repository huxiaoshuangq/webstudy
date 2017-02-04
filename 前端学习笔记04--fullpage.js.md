### 前端学习日志-04
用fullpage.js全屏滚动插件和move.js动画插件
可以做一个单页网站  

---
目前想的项目是:

- 武汉义工联静态导航
- 个人简历
- 产品宣传页[最好加入vidoe展示元素]

---
> 参考网址和文档  


- fullpage.js  [github主页](https://github.com/visionmedia/move.js)
- move.js      [github主页](https://github.com/visionmedia/move.js)`|  [文档](http://visionmedia.github.io/move.js/])

---
### 学习Note
关于fullpage.js

- 需要掌握基本的html文档结构
- 熟悉提供的api函数

比如:

![mark](http://oe40n695u.bkt.clouddn.com/blog/20170205/024839596.png)

---
想要用到的功能接口:
- 设置顶部固定导航菜单 [锚链接]
- 右侧导航的小圆点
- 点击小圆点跳转页面时有提示条[tooltip]
- 还要设计一个固定元素[如QQ交谈按钮]
- 各种页面载入,进入,离开的回调函数接口
---

> 关于move.js  

在官网文档中,有详细的动画效果
和api接口代码
可以实现的动画包括:
- 放大缩小
- 显示隐藏
- 快速移动
- 旋转

---

### 接下要做的事情
- 写需求文档
- 设计网页,准备素材
- 编写基本的额html/css样式
- 用fullpage.js的回调函数触发move.js的动画

        需要注意的是:设置动画后
        还要设置页面离开时还原动画
        不然重复浏览时,动画只会显示一次.

---



