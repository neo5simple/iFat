# iFat

软妹子们，还在为体重发愁么？

来用这款软件来记录咱的体重变化吧，每小时的、每天的、每周的、每月的甚至  
每年的，看看图表中的自己是如何克服地球引力一点一点瘦下来吧 =v=

![iFat - web.png](https://raw.github.com/neo5simple/iFat/master/ic_launcher-web.png)

软件名称上欢迎大伙来吐槽，愿大伙与肥肉相处愉快~

## 目的

为老婆大人做体重统计图，精细到到某个小时的变化，然后再整个靠谱的算法把数据弄  
成平滑的曲线，以后还可以拿出某两天、某两个周做图形比对。

## 需求说明

+ 记录当前时间的体重
+ 统计数据绘制对应尺度的图表
+ 根据统计结果，得出人体体重变化规律，方便在适当的时机给予肥肉们致命打击
+ 给某次测量结果打标签，备注测试前后所处的状态等
+ 导出数据，或者同步到其他手机 *[待定]*

## 开发

斑驳现在也就能会做 Android 平台的，所以就不去扯什么跨平台了。全部代码都会在  
GPL v3 协议下发布，并在 Git 中将每个开发过程都打上标签，暂定为以下几个环节：

+ init: 初始化工程，需求文档等
+ layout: 大致界面布局设计
+ logistics: 大致逻辑事物流
+ chart: 图表视图设计
+ algorithm: 算法处理数据
+ others: 测试标签、时机提示等用户体验环节
+ productivity: 导出、同步、测试等

当然，如果您也有兴趣，十分欢迎参与到 iFat 项目，不过，斑驳在编程上的小洁癖；  
至于中间件由作者设定发布等级、支配权，当然，如果您发现了其中潜在商业价值，  
请不要客气的拿到您的生产环境中去。

## 更新

### 3.18

除去前段时间瞎胡闹，iFat 实际开发时间已过了一周，看看斑驳都做了些啥：

+ 初始化工程，打了个标签
+ 划分大致的界面布局以及事物流，开发比较随性，事后一块补上标签，哈
+ 每天的图表设计，完全代码手绘，比较疲劳
+ 换高分辨率手机测试，惨败，各种参数的修改ing
+ 现阶段用户每天的行为基本完结，放到根目录上一个 apk 大伙来找茬

**TODO**

+ 细化布局，在合适的位置打标签
+ 转战周图表
+ 设计周曲线图绘制算法

欢迎访问: [俺的博客](http://neo5simple.diandian.com)

祝好，  
斑驳敬上

