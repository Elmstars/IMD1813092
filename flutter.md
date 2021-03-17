# flutter

## flutter简介

Flutter是谷歌的移动UI框架，可以快速在iOS和Android上构建高质量的原生用户界面。 Flutter可以与现有的代码一起工作。在全世界，Flutter正在被越来越多的开发者和组织使用，并且Flutter是完全免费、开源的。

## Windows上的flutter

### 系统配置

1. 操作系统：Windows 7 SP1 或更高的版本（基于 x86-64 的 64 位操作系统）。
2. 磁盘空间：除安装 IDE 和一些工具之外还应有至少 1.32 GB 的空间。
3. 工具：要让 Flutter 在你的开发环境中正常使用，依赖于以下的工具：
   - Windows PowerShell 5.0 或者更高的版本（Windows 10 中已经预装了）
   - Git for Windows 2.x，并且勾选从 Windows 命令提示符使用 Git 选项。
   - 如果 Windows 版的 Git 已经安装过了，那么请确保能从命令提示符或者 PowerShell 中直接执行 git 命令。

### 获取 Flutter SDK

### 更新 path 环境变量

1. 在开始菜单的搜索功能键入「env」，然后选择 编辑系统环境变量。
2. 在 用户变量 一栏中，检查是否有 Path 这个条目：
   - 如果存在这个条目，以 ; 分隔已有的内容，加入 flutter\bin 目录的完整路径。
   - 如果不存在的话，在用户环境变量中创建一个新的 Path 变量，然后将 flutter\bin 所在的完整路径作为新变量的值。

### 运行 flutter doctor

    `C:\src\flutter>flutter doctor`

## 编辑工具设定

### 设置 Android 开发环境

- [Android Studio](https://developer.android.google.cn/studio)，3.0 或之后的版本. 
同时, 你也可以使用 IntelliJ：
- [IntelliJ IDEA Community](https://www.jetbrains.com/idea/download/#section=windows)， 2017.1 或之后的版本. 
- [IDEA Ultimate IntelliJ](https://www.jetbrains.com/idea/download/#section=windows)， 2017.1 或之后的版本. 

### 安装 Flutter 和 Dart 插件

1. 打开插件偏好设置 (位于 File > Settings > Plugins)
2. 选择 Marketplace (扩展商店)，选择 Flutter plugin 然后点击 Install (安装)。
