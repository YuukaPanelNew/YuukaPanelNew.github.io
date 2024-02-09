---
#menu_id: wiki
wiki: yuukapanel # 这是项目id，对应 /data/wiki/hexo-stellar.yml
title: 全新的开服体验-幽香面板
---

## **幽香面板 四周年诚意之作**

幽香面板是一个小巧精致的开服面板

前置环境：[NET8](https://dotnet.microsoft.com/zh-cn/download/dotnet/8.0)

**功能介绍：**

1. 性能监控：在面板界面左上角常驻显示CPU和内存的使用占比

2. 多服务器管理：一个面板可同时管理多个服务器，或管理多个不同游戏的服务器（目前支持原生BDS、BDSLL、JE、幻兽帕鲁等）

3. 快捷操作：继承于幽香面板2，服务器配置页面可快捷发送指令，添加或移除白名单、管理员，踢出玩家等

4. 性能限额：可自由限制或预留，服务器可使用的物理内存，CPU占用率**【首创】**

5. 日志记录：使用csv格式记录日常日志，可便捷查看历史日志信息；使用txt单独记录错误日志详情信息

6. 定时任务：可自定义任务执行的时间、循环周期。可自定义任务命令，多行命令实现更为复杂的操作

7. 备份管理：面板集成BDS的冷、热备份方案，支持原版服务器，不用担心插件兼容问题

8. 资源释放：正常关闭面板时，面板会自动关闭服务器并释放其所有资源，防止服务器被意外关闭

**开发计划：**

{% checkbox checked:false 拓展功能：对接OpenFrp，实现家里云快速开服 %}

{% checkbox checked:false 面板接口：提供WebSocket接口，未来可对接机器人或远程管理等 %}

{% checkbox checked:false 更多游戏：支持更多游戏服务器的管理 %}

## 安装与更新

{% box %}
{% tabs %}

<!-- tab 桌面应用版 -->

### **安装方法**

### 1. 下载面板

进入幽香面板[下载地址](https://www.minebbs.com/resources/7150/)，您将看到以下内容

请根据所运行面板的**服务器系统**进行选择合适的面板文件
![img](https://lfs.k.topthink.com/lfs/16b64f7f09e9105ad7147c8a405d961cfe399a9565a3810fa87a600a160a6640.dat)
下载完成后，请将面板文件放入一个**单独的**，**纯英文**目录下

### 2. 下载 .NET 8 桌面运行时

进入 [.NET 8 下载页面](https://dotnet.microsoft.com/zh-cn/download/dotnet/8.0)下载.NET 8 桌面运行时
![img](https://lfs.k.topthink.com/lfs/61c87fc1a52ac1eee6e561333270f480fe14e19f2f3c6f24e56a8f6fb4e5bf53.dat)
依旧是根据**服务器系统**选择适合的 ( x64或x86 ) 文件进行下载
然后，双击安装你所下载的文件

### 3. 使用面板

双击打开面板文件，面板会在该目录下自动生成.server和.log文件夹，分别用于储存服务器文件以及面板、服务器运行时所产生的日志信息
![img](https://lfs.k.topthink.com/lfs/a43e1ffc59db493317b165292354dc0641c90c48fadc98ca91440fd69919231a.dat)
至此，面板的安装已完成

### **更新方法**

1. 下载新版压缩包

1. 覆盖幽香面板.exe


{% note color:green 适用范围 懒人体验追求稳定和可靠性的用户。 %}

<!-- tab 命令行版 -->

**安装方法**

**更新方法**

{% note color:yellow 适用范围 无桌面环境和有动手能力的用户。 %}

{% endtabs %}
{% endbox %}

{% toc wiki:Stellar 文档目录 display:mobile %}
