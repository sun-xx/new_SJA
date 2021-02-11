# Scratch Json Analyser
**sja核心已经弃用，换成pyscratch，更多关于新核心的信息，在文档末尾有介绍**  

## 简介

Scratch Json Analyser，简称 SJA，是由孤言发起的针对 Scratch3 Json 文件的比对工具。
原先的[Scratch 版](https://www.aerfaying.com/Projects/512945)在 A 营发布。
为响应用户的文件分析和比对需求，解决原来分析器效率低下的问题，决定采用 Python 来编写这个项目。  
[国内仓库](https://www.gitee.com/gitkunkun/SJA)  
这个版本是sun-xx精简后，只剩内核与GUI的版本，去除了~~简陋的~~文档和旧内核以及命令行界面。  

SJA 主要具有代码结构分析功能。  

## 小白专区
下载exe文件：https://gitee.com/gitkunkun/sja-bin  
在线体验：http://kunkunpaw.pythonanywhere.com/

------- 小白止步 -------

## 安装配置
首先确保你有Python3，然后克隆这个项目到本地
### 命令行版启动
在你的终端（Windows是cmd）里安装依赖模块：  
```shell
cd SJA
pip3 install -r requirements.txt --i https://pypi.douban.com/simple
```
依赖安装好以后，进入GUI文件夹，运行start.py  
就可以运行了  
### Web版
**待补充**  

## pyscratch的使用
详见pyscratch/tutorial.py
**待补充**

### GUI

这是 GUI 界面，意味着你可以通过点点点的方式分析文件。  
2021/2/11由sun-xx开发完成 

## 原理

scratch3 文件用 zip 格式打开后，会有一个 project.json 文件。  
程序通过分析这个文件，来统计代码块数等信息。

## 主要开发者

[kunkun](https://github.com/kunkunhub) : 核心开发者

[sun-xx](https://github.com/sun-xx) : UI开发者

[孤言](https://github.com/GuYan1024) : 发起者

## 参与贡献

如果你想一起开发这个项目，有以下几个途径：

1. 提交 pull request，分享你的解决方案
2. 提 issue，告诉我们程序的 bug 和建议
3. 根据issue和代码里的TODO，尝试解决

:-)
