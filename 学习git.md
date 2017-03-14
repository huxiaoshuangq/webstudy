### 为什么学习git

![mark](http://oe40n695u.bkt.clouddn.com/blog/20170314/221244310.png)
 
---

#### 初见
最初用github，是按照网上的教程
搭建了一个免费Hexo静态博客
很喜欢，也写了很多文字

#### 学习脚本语言
后来，学习脚本语言的时候，发现github是一个宝库
有很多优秀的开源项目
于是在慕课网上看了`github版本控制`这门课程

#### 迷蒙的认识
![mark](http://oe40n695u.bkt.clouddn.com/blog/20170314/221252159.png)

 
更深入的了解的github的issue，pull resquest，magin等团队协作流程
可以在上面分享公开自己的项目源码
可以当作云笔记
不过最喜欢的还是github.io和gh-pages的静态页面解析服务
可以方便的搭建各种静态网页展示
比如fulllpage.js
比如bootstrap
还有vue·`npm run build`之后的生产文件

#### 现在 learn git
git 和 github 是不一样的
前者是软件，或者说命令行
后者是网站
因为想把看到的一个vue wechat项目打包后
![mark](http://oe40n695u.bkt.clouddn.com/blog/20170314/221259757.png)

 
用github pages上线
结果网页版有内容上传限制和诸多不稳定

---

### 学习笔记

> 以下是在通勤的路上
> 边用pad边看视频用手机记录的wizinote：
![mark](http://oe40n695u.bkt.clouddn.com/blog/20170314/221304533.png)

 


Git 北京  小书下载
Coding 国内网站

Github 网站
Git是软件
用命令行

注册github ，私有仓库付费
新建仓库

下载desktop.github.com客户端
登录账户
Clone到本地

安装mac的 home brew 
Brew install  git 
找到仓库的https连接进行克隆


在客户端中创建仓库的2种方式
命令行创建仓库
1makedir新建文件夹📂
2.git init 初始化仓库，自创建.git文件夹，但是github 默认隐藏


删除仓库，网页，本地，命令行

查看版本修改记录
Git status
提交修改  客户端commi 然后sysc
命令行git add  -A
提交 git commit  -m“这里写更新留言”

版本回滚

Sync更新和同步变化


---
### 纸质笔记复盘
另外也在休息的时候用A4纸写了一些笔记
现在将它电子化：  
#### 用https同步github与本地仓库
https与ssh的区别在于，配置了ssh之后，不用每次输入账号密码
mkdir demo 新建demo文件夹
cd deco     进入demo
git init     初始化为git仓库
git remote add origin httpsurl  同步远程仓库通过https
git push -u origin master        推送到master主分支
输入账号密码

#### 配置sshkey
ssh-key
回车回车回车
cd .ssh
ls
id.rsa.pub 用sublime打开拷贝钥匙
进入github网页的设置
输入sshkey保存
git push -u origin master
git config --global push.default simple 设置远程与本地的关系
cd -  返回原目录

---
### 分支
git checkout 分支   切换至分支目录
git brauch -D 分支   删除分支

---
### github pages
![mark](http://oe40n695u.bkt.clouddn.com/blog/20170314/221308612.png)

 
可以新建用户名.github.io仓库
也可以主分支下新建gh-pages分支
用来展示静态网页

---

### 最后
![mark](http://oe40n695u.bkt.clouddn.com/blog/20170314/221314538.png)

 
我的vue 执行 npm run build 后
部署到github github pages
依~然~没~有~成~功,泪奔
有谁可以告诉我么
