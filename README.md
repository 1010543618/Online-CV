# online-resume

示例：https://zjffun.github.io/online-resume/

首先在线简历的好处有很多，我就不一一列举了，直接进主体。

## 设计

先弄清楚最后想要做出来什么东西是个好习惯，整理整理要实现的功能，要显示的内容，整个页面的布局和颜色、整体的架构（做个在线简历这么小的东西就用不上了），用到的框架、库、工具什么的。

### 功能

1. 导出 HTML 和 pdf 功能：这个简历以后会用到其他地方肯定是要导出的。主要要实现导出 pdf 因为别的格式都有弊端（如，图片：无法复制，HTML：hr 可能使用错误地软件打开）。
2. 国际化功能：让世界看到你的简历 —— Online-CV 相信咸鱼的力量！

### 内容

对智联、拉钩、BOSS直聘等招聘网站简历需要填写的内容整理了一下，取其精华得到 以下内容：

- 个人基本信息
- 技能
- 工作经验
- 项目经历
- 教育经历
- 自我描述
- 社交主页
- 作品

### 页面

1. 个人信息和和下面的项目纵向排列：网上有一些是将个人信息放在侧边的设计 ，但这样适合一页的应届生简历，超过一页侧面就很尴尬了。
1. 移动端适配：肯定要在移动端上可以看的
1. 整体背景为浅绿色：这~~就是爱情~~样护眼嘛

### 技术

Webpack、Babel是肯定要用的、之后做成用 YAML 配置内容、打印还会加

## 实现

## 注
查了一下 CV 和 Resume 不是一回事。。[CV和Resume到底是有什么，有什么差别？](http://www.sohu.com/a/235874375_372460)

