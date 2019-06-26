# czc

A new Flutter project.

## Getting Started

入门级Flutter搭建教程

1，所需工具以及依赖：(1)Git命令行工具 (2)Flutter SDK (3)Android Studio  (4)VS Code

2,获取Flutter SDK
(1)官网下载地址  https://flutter.dev/docs/development/tools/sdk/releases#windows
(2)将安装包zip解压到你想安装Flutter SDK的路径（如：C:\src\flutter；注意，不要将flutter安装到需要一些高权限的路径如C:\Program Files\）。
(3)在Flutter安装目录的flutter文件下找到flutter_console.bat，双击运行并启动flutter命令行，接下来，你就可以在Flutter命令行运行flutter命令了。


3，更新环境变量 “控制面板>用户帐户>用户帐户>更改我的环境变量>用户变量”
(1)条目Path，然后将 flutter\bin的全路径作为它的值.
(2)条目PUB_HOSTED_URL，值https://pub.flutter-io.cn
(3)条目FLUTTER_STORAGE_BASE_URL，值https://storage.flutter-io.cn


4,安装Android Studio
(1)下载并且安装 地址：  https://developer.android.com/studio/index.html
(2)启动Android Studio，然后执行“Android Studio安装向导”。这将安装最新的Android SDK，Android SDK平台工具和Android SDK构建工具，这是Flutter为Android开发时所必需的


4,配置VS Code
(1) 调用View>Command Palette…
(2) 输入 ‘install’, 然后选择 Extensions: Install Extension action
(3) 在搜索框输入 flutter , 在搜索结果列表中选择 ‘Flutter’, 然后点击 Install
(4) 选择 ‘OK’ 重新启动 VS Code

配置好后可在命令行执行 flutter doctor，看一下差哪些没有配置

5,创建一个flutter Demo
(1)启动 VS Code
(2)调用 View>Command Palette…
(3)输入 ‘flutter’, 然后选择 ‘Flutter: New Project’ action
(4)输入 Project 名称 (如myapp), 然后按回车键
(5)指定放置项目的位置，然后按蓝色的确定按钮
(6)等待项目创建继续，并显示main.dart文件

6,就可以在手机跑起来啦
