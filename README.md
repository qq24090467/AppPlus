# App+ #
### 介绍 ###
App+是一个可以用于传送Apk文件，提取APK文件等的工具软件。<br>
目前已开源，涉及到了一些知识点，如Material主题切换、design包使用。欢迎学习交流。


### 开发初衷 ###

* <b>优雅体面的提取APK</b><br><br>在工作过程中，有时需要反编译一些软件的APK，此时这些软件就存在于自己的手机，但是无法直接获得从手机中获取APK，后来在软件市场找到了一些相关的APK提取工具软件，
如APK提取器等等的软件，但是无一例外，它们的操作体验都太差，加上丑陋的广告，让我一点都忍不了。所以我觉得自己有必要让这个看似简单的事情，变得更加优雅。<br><br>
* <b>快速打开应用详情</b><br><br>在开发过程中，经常需要去应用详情界面中执行清除数据的操作。但是一般的ROM（MIUI做的不错，可以直接在最近任务列表，长按对应APP的图标，就可以打开应用详情）都只能去设置界面，然后找到对应的应用，点击item，打开详情，点击清除数据，整个过程稍微复杂。所以如果有一个app，可以显示最近打开的应用列表，并且支持打开应用详情最好不过了。<br><br>
* <b>快捷分享应用APK文件</b><br><br>这个功能跟茄子快传、快牙提供的功能是重合的，但是它们正常工作的基础是双方手机必须同时安装客户端，其实不该这么霸道的。App+可以单向传送APK文件到对方手机，尽管速度慢一点。<br><br>
* <b>喜欢MaterialDesigner</b><br><br>不久前，Google公布了support:design包，很好的支持了MaterialDesigner的新元素,所以可以通过项目，学习使用最新的API。（有人说，可以在工作中就可以使用相关的API啊，但是无奈，公司的设计都是按照IOS的规范，MD根本没影）


### 下载地址 ####

[fir下载](http://fir.im/appplus)<br>
[小米应用商店](http://app.mi.com/detail/104777)

### 截图 ###

![index](/art/index.png "")
![send](/art/send.jpg "")<br>
![setting](/art/setting.png "")
![theme](/art/theme.png "")

### 知识点 ###
* 主题切换
* Logger管理
* 友盟统计 包括事件统计以及自动更新

### 更新日志 ###

* 0.2.3

        新增：引入Square的leakcanary，用于检测内存泄露(09-04)
        新增: 加载动画以及空信息提示(09-03)
        新增: 主页右上角增加意见反馈入口(09-03)
        更新: 改变应用启动图标(09-03)
        修复: 完成搜索后，滑动效果bug(09-03)

* 0.2.2.1

        优化: 手动更新时给出更新结果提示(08-23)
        移除: Overflow菜单中的分享好友选项(08-23)

* 0.2.2

        新增：友盟统计（事件统计，软件自动更新）(08-22)
        新增: 再按一次退出机制(08-22)
        移除: 主页右上角设置入口(08-22)
        移除: 开发者选项设置(08-22)
        移除: 侧滑菜单交互(08-22)

* 0.2.1

        新增: 主题颜色设置（可以为应用设置你喜欢的主题颜色啦）
        新增: 最近打开列表是否显示App+的设置选项
        修复: 修复Android5.0以上设备的StatusBar颜色异常问题
        修改: 联系方式(微博)
        移除: 切换夜间模式和白天模式

### License ###

         GNU GENERAL PUBLIC LICENSE  Version 3, 29 June 2007

         Copyright (C) 2007 Free Software Foundation, Inc. <http://fsf.org/>
         Everyone is permitted to copy and distribute verbatim copies
         of this license document, but changing it is not allowed.