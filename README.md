# Android 寒假考核作业

> Android第二学期的培训将采取导师制
>
> 本次考核成绩将作为分配导师的重要参考，所以请大家认真对待这次的考核作业
>
> 没有完成本次考核作业或抄袭/敷衍了事的同学视为主动退出，将不参与下学期的培训
>
> 下学期第一节课会让你们当众展示，讲解你们的APP，请提前做好准备

## 必读：

### - 假期建议：

+ 认真复习所学知识，如果之前进度跟不上，寒假是一个很好的追赶机会
+ 学习并使用搜索引擎，但**禁止**大面积复制网上代码
+ 确保有能自由科学上网的能力，时间充裕的情况下可以尝试自己搭建梯子

### - 作业要求

+ `APP兼容到4.0，Api 14`
+ 将项目push到**GitHub**
+ 本次作业使用加分制而非等级制，请为了加分项尽量展现你的能力吧~
+ 学习`Markdown`语法，填写**README**中介绍你的APP，内容包括：
  + 作者(你)对作品的描述/感受/体会
  + 功能及操作方式，并附上截图（最好是Gif）
  + 简要提及实现功能所使用到的技术/知识点
  
### - 提交相关

+ 截止时间：2019-03-01 23：59前
+ `邮箱`：mredrock@163.com
+ `邮箱标题`：`寒假考核-name-number` 例：寒假考核-李吉-2016233333
+ `邮件正文`：此项目的GitHub仓库地址
+ `邮件附件`：APP的正式版安装包

### - 加分项

+ 功能完整，实现项目提供的大多数Api
+ 图片缓存：加载过的图片保存在本地，优先从本地读取图片
+ 数据缓存：加载过的数据保存到本地，在网络错误时加载本地缓存
+ 规范命名，封装合理，逻辑清晰，良好的代码风格
+ 好看的UI，不同机型的适配
+ 自定义控件，自己设计的自定义View
+ 适配Android系统，如 6.0 运行时权限，8.0 通知
+ 自己封装工具类 **(有一定难度，锻炼性大)**
+ 自己实现/实现部分的后端Api **(有一定难度，分值较大)**

## 作业选项：

### 一. 做一个自己想做的APP

做一个自己想做的APP，自由发挥，根据完成情况和功能难度打分

> 若成品过于简略，可能被视为不合格作品

### 二. 曾入选Api

曾经的考核选项，可供参考

#### 1. 图灵聊天机器人

[图灵](http://www.tuling123.com/)是一个聊天机器人，通过申请账号，可以使用该网站提供的Api。

请使用其提供的Api，制作一个`Android`端的聊天机器人，要求能保存历史聊天记录。

#### 2. Postman

> Developers use Postman to build modern software for the API-first world

[Postman](https://www.getpostman.com/) 是一个强大的API测试工具

学习一下Postman的使用方法，并做一个`Android`端的`Postman`

> 关于HTTP网络协议方面，时间充裕想补的，可以看看《图解HTTP》

#### 3. 知乎日报

[Api文档](https://github.com/izzyleung/ZhihuDailyPurify/wiki/%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5-API-%E5%88%86%E6%9E%90)

这是`知乎日报`的部分Api文档，仿写知乎日报APP

#### 4. 今日头条

[Api文档](https://github.com/iMeiji/Toutiao/wiki/%E4%BB%8A%E6%97%A5%E5%A4%B4%E6%9D%A1Api%E5%88%86%E6%9E%90)

这是`今日头条`的部分Api文档，仿写今日头条APP

#### 5. 逼乎

[Api文档](https://github.com/jay68/bihu_web/wiki/%E9%80%BC%E4%B9%8EAPI%E6%96%87%E6%A1%A3)

`逼乎`是以前的Android学长仿照知乎写的问答平台Api，你可以自定义UI实现Api

#### 6. Gank

[Api文档](https://gank.io/api)

`Gank干货集中营`是一个技术干货分享网站

### 三. 更多选项

[选项列表](https://github.com/jokermonn/-Api)

列表中的选项实现难易度未知，Api坑度未知，请自行踩坑

当然，你也可以去别的什么地方找你想要的Api，然后实现那个APP

或者自己实现后端，做独特的APP，加油哦~

## 选读：深入学习与提高

> 在准备深入学习和提高前，请确保你已经认真复习了Java基础，Android基础

### 一. 关于WEB

> WEB可以不懂Android，Android不能不懂WEB

#### 前端：

了解，学习`html`，`css`，`JavaScript`，学一些基本的`DOM`操作，会写一些简单的网页，大约耗时2周。

#### 后端：

搭建一个服务器（`腾讯云`或者`阿里云`均有学生优惠，国外的`DO`有Github学生优惠，送50刀）

入门一门后端开发的语言（`Java EE`、`PHP`、`Python`，`GO`，`NodeJS`......），其中PHP最为简单，实例可以查看上文中的`逼乎`Api

### 二. 关于Git

> 挺重要的东西

[廖雪峰教程](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000) 建议有空还是刷一遍这个，做一份笔记，可以附在作业里，加分

### 三. 关于Android开发进阶

> 不是要你们单纯的会用，也不是一定要这个寒假一下子就全都学会，先了解是做什么用的，然后使用它，最后要懂原理

#### 网络请求

+ OkHttp
+ Retrofit

#### 图片加载

+ Picasso
+ Glide
+ Fresco

#### Json解析

+ Gson（顺便了解下Android Studio插件Gson Format）
+ Jackson
+ FastJson

#### 事件总线

+ EventBus
+ Otto

#### 性能优化/内存检测

+ LeakCanary
+ Android Studio自带的分析工具

#### 数据库

+ GreenDAO
+ OrmLite
+ LitePal
+ Realm
+ **Room**

#### 依赖注入

+ ButterKnife
+ Dagger2
+ RoboGuice

#### 跨平台框架

+ React Native
+ Weex

#### APP架构

+ MVP
+ MVVM（DataBinding）

#### 响应式编程

+ RxJava 1.x
+ RxJava 2.x
+ RxAndroid
+ RxBus
+ RxLifeCycle
+ RxBinding

#### Kotlin

> 在Java学习的差不多之后开学，推荐《Kotlin开发实战》

+ lamda表达式
+ 可空性表达 与 类型判断
+ 运算符重载
+ 扩展方法
+ 代理
+ DSL
+ Kotlin Android Extensions
+ Anko

### 写在最后

今年的寒假时间稍微有点少，考虑到时间问题，会降低考核门槛，请在动手写考核前先复习之前的知识。另外，如果的确想继续学习Android开发，那么这个假期就是一个很好的学习机会，很可能一个假期回来后你们之间的差距将会被拉大。之前学习上比较吃力的同学也不要灰心，可以利用这个假期多看看书，复习、预习一下，为第二学期的学习打好基础。

能写出一个APP你就已经跑在**大多数人**前了，回想当时被站满的2117教室后排，现在的你和你竞争的对手，都是少数的精英了，在这群人之间，你能走多远呢？

请拼尽全力继续努力吧

最后祝大家新年快乐，2019不熬夜，拥有浓密秀发！

![绝不熬夜](img/sleep.jpg)
