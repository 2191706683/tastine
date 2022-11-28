# 塔斯汀小程序模仿项目
- 本项目归塔斯汀所有， 只做学习所用， 请尊重原厂版权
- 可以监听访问数据  fiddler 抓包工具 抓取图片
- 界面模仿采用markdown做标记
  1. 我们没有设计稿， 如何1：1 还原小程序？
  2. 拍屏得到小程序
  3. 使用在线大小[转化工具](https://www.gaitubao.com/), 将图片改成750
    以后在写wxss的时候，直接量像素就可以写进去， 因为小程序以750rpx作为设计稿标准大小帮我们自动适配，很好用。
  4. 使用[markman](http://www.getmarkman.com/) 先标注，在写样式以后，上了班就不用了，会有设计师给标好的
  现在，还是DIY吧

- 项目配置在根目录下
  - 隐藏并定制navigationBar
    "navigationStyle": "custom"
  - 启动定位功能

- 使用了BEM 国际css命名规范
  tst_banners 广告位
  tst_banners__img Element

- css 技巧
  1. 能不用定位就不要用定位
    脱离文档流
  2. 移动端多用弹性布局

- git 提交
