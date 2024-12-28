## 思维导航

* [前言](https://github.com)
* [项目介绍](https://github.com)
* [软件架构](https://github.com)
* [项目特点](https://github.com)
* [Visual Studio插件安装](https://github.com)
* [项目源代码](https://github.com)
* [案例演示效果](https://github.com)
* [项目源码地址](https://github.com)
* [优秀项目和框架精选](https://github.com)

## 前言


在咱们的印象中C\# WinForm一直只支持Windows系统运行，无法支持跨平台运行。今天大姚给大家分享一个开源框架：`GTKSystem.Windows.Forms`，它能够让C\# Winform支持跨平台运行。


:[FlowerCloud机场订阅官网](https://hanlianfangzhi.com)## 项目介绍


GTKSystem.Windows.Forms是一个C\#桌面应用程序跨平台（Windows、Linux、macOS）开发框架，基于GTK组件开发。使用该框架开发项目时，Visual Studio可以使用C\#的原生WinForms表单窗体设计器，保持与原生WinForms相同的属性、方法和事件，无需额外学习。通过一次编译，可以实现跨平台运行，便于开发跨平台WinForms软件，以及将现有的C\# WinForms软件升级为跨平台软件。


![](https://img2024.cnblogs.com/blog/1336199/202412/1336199-20241227221542187-2056175854.png)


## 软件架构


使用GTK3\.24\.24\.95作为表单UI重写C\#的System.Windows.Forms组件，在应用时，兼容原生C\#程序组件。


## 项目特点


* 跨平台性：支持Windows、Linux和macOS三大主流操作系统。
* 易用性：无需学习新的开发语言或框架，直接使用C\#和原生WinForms开发。
* 高效性：一次编译即可在多个平台上运行，减少开发成本和时间。


## Visual Studio插件安装


1. 从NuGet上安装GTKSystem.Windows.FormsDesigner类库，此类库可以在编译工程时修正窗体设计器。
2. 下载本插件工具，关闭Visual Studio 2022，直接双击GTKWinformVSIXProject.vsix文件安装（本框架下的工程，Studio没有添加Form模板项，需要安装此插件）。


**插件会安装两个功能：**


* 1、新建项的Form窗体模板、用户控件模板。
* 2、工程右键菜单。


![](https://img2024.cnblogs.com/blog/1336199/202412/1336199-20241227221556076-1583166484.png)


## 项目源代码


![](https://img2024.cnblogs.com/blog/1336199/202412/1336199-20241227221606886-1473190655.png)


## 案例演示效果


![](https://img2024.cnblogs.com/blog/1336199/202412/1336199-20241227221618536-730358450.png)


![](https://img2024.cnblogs.com/blog/1336199/202412/1336199-20241227221623402-1282990179.png)


![](https://img2024.cnblogs.com/blog/1336199/202412/1336199-20241227221630890-865059707.png)


![](https://img2024.cnblogs.com/blog/1336199/202412/1336199-20241227221636044-1337399251.png)


![](https://img2024.cnblogs.com/blog/1336199/202412/1336199-20241227221642003-947540216.png)


## 项目源码地址


更多项目实用功能和特性欢迎前往项目开源地址查看👀，别忘了给项目一个Star支持💖。


* GitHub开源地址：[https://github.com/easywebfactory/gtksystem\-windows\-forms](https://github.com)
* Gitee开源地址：[https://gitee.com/easywebfactory/gtksystem\-windows\-forms](https://github.com)


## 优秀项目和框架精选


该项目已收录到C\#/.NET/.NET Core优秀项目和框架精选中，关注优秀项目和框架精选能让你及时了解C\#、.NET和.NET Core领域的最新动态和最佳实践，提高开发工作效率和质量。坑已挖，欢迎大家踊跃提交PR推荐或自荐（让优秀的项目和框架不被埋没🤞）。


* GitHub开源地址：[https://github.com/YSGStudyHards/DotNetGuide/blob/main/docs/DotNet/DotNetProjectPicks.md](https://github.com)
* Gitee开源地址：[https://gitee.com/ysgdaydayup/DotNetGuide/blob/main/docs/DotNet/DotNetProjectPicks.md](https://github.com)


 
