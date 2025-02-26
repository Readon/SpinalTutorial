# SpinalHDL Tutorial Project

这个仓库从[SpinalTemplateSbt](https://github.com/SpinalHDL/SpinalTemplateSbt)发展而来，用于一步一步指导SpainlHDL入门


## 安装环境

- 安装版本管理软件[Git for Windows](https://git-scm.com/downloads/win)和图形界面[GitExtensions](https://gitextensions.github.io/)
- 安装基于MSYS2的开发环境[SpinalHDL-installer](https://github.com/Readon/SpinalHDL-installer)
- 安装编辑器VSCode和相关插件,[Metals](https://marketplace.visualstudio.com/items?itemName=scalameta.metals)和[Vaporview](https://marketplace.visualstudio.com/items?itemName=lramseyer.vaporview)

## 测试开发环境是否搭建成功

- 从启动菜单启动MSYS2 MINGW64环境
- 使用`cd /x/xxxx`切换目录到本仓库路径。
	若不知道'/x/xxxx'如何编写，可以用文件管理器打开本仓库，地址栏内本地地址形如"C:\SpinalTutorial"字符串复制，执行`echo "C:\SpinalTutorial" | dos2msys`获得目录。
- 执行`sbt "runMain projectname.MyTopLevelSim"`测试环境是否安装成功。
