华南理工大学软件开发综合实训项目-锄大地游戏设计与实现
2025/5/13 - 2025/7/*

# SCUT-Repo-CCDGame


## clone放置位置(在Clone 本仓库之前必须阅读！)

在 安装Android Studio 的时候已经成功的 创建了如下项目结构：
```
D:\Android                  # 这里可以改为C盘或者其他盘都行
├── Android Studio/         # Android Studio 程序安装目录
├── AndroidStudioProjects/  # Android 项目文件目录
├── GradleRepository/       # Gradle 本地依赖仓库
└── SDK/                    # Android SDK 目录
``` 
clone的位置是在 `D:\Android\AndroidStudioProjects` 下。

clone 后的目录结构应当是：
```
D:\Android
├── ...                             # 省略的其他目录
└── AndroidStudioProjects           # 项目总目录
    ├── MyProject                   # 我创建的测试项目
    │   ├── app
    │   └── gradle
    ├── SCUT-Assignment-CCDBysenior # "遗产"项目
    │   └── SCUT-Assignment-CDD
    └── SCUT-Repo-CCDGame           # 实际的Android Studio 项目
        └── CCDGame
```

## 进行你的第一个提交之前需要阅读的
### 必读
- [秒懂Git之配置(配置git默认编辑器为vscode或者notepad++)](https://blog.csdn.net/ShuSheng0007/article/details/115449596)：配置命令行git 操作的默认编辑器为 vscode 可以让你在撰写 commit message ，修改git config 文件的时候如虎添翼。
- [Git Commit 之道：规范化 Commit Message 写作指南](https://blog.csdn.net/hzf0701/article/details/134367234):规范化commmit格式可以让团队成员之间的沟通更加顺畅。
## 推荐
- [Learning Git Branch](https://learngitbranching.js.org/)：一个交互式的学习github命令行操作的网站，强烈推荐。
## 选读


## 仓库结构介绍

根目录下是与项目有关的文档，视频，图片存储的地方。
目录 `./CCDGame` 存放了在Android Studio 中打开的项目文件.

## 项目简介

### 项目目标
（1）	理解学习软件开发的过程，能够利用UML进行UP迭代开发，在实验中深刻理解用例需求分析、面向对象分析、面向对象设计。
（2）	深入理解Android开发的过程，实践Android游戏项目的开发和功能实现。
（3）	在迭代团队开发中锻炼协作和合作能力，以及SCRUM敏捷项目管理能力。
（4）	实现一款锄大地扑克牌游戏。

### 项目依赖技能

- [x] Android Studio环境配置学习
下载Android studio安装包，并进行了安装配置，在选择了合适的android sdk manager之后进行了下载，并尝试建立了一个新的项目作为运行测试。开启后，下载了gradle文件，进行了gradle文件配置，随后尝试新建了一个安卓虚拟机，在虚拟机上将第一个测试程序放入测试，经过对配置文件的下载和调试，最后成功运行测试程序，Android studio平台搭建完成。
- [ ] git 与 github 及相关协作技能学习
- [ ] 使用UML 以及 OOA 对项目进行建模并且形成项目文档。
- [ ] MVC 架构学习
- [ ] 软件界面及接口实现 学习
- [ ] Android Studio 蓝牙开发

### 项目特点
（1）掌握starUML进行UML7大图建模                                                                     
（2）进行需求分析和面向对象的设计，并且进行分析建模和设计建模。
（3）详细设计时，注意引入必要的设计模式，优化设计。                                                                  
（4）完成UI的界面设计，实现不同页面的切换。                                                                       
（5）适配玩家自由选择南北方规则的不同玩法。                                                                     
（6）实现用户间的蓝牙，WIFI连接，提供多名玩家联机对战功能。
（7） 对扑克牌博弈AI模块，提供不同AI算法实现策略，软件适配不同的AI博弈算法模块。 至少2钟AI算法策略，需要使用策略模式。   


