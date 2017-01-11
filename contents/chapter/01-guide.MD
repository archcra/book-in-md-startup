# 使用指南

## 环境准备
### git
git的安装请参考这里： https://git-scm.com/book/en/v2/Getting-Started-Installing-Git


### 安装Multimarkdown
在这里下载安装文件：
https://github.com/fletcher/MultiMarkdown-5/releases
以2016年5月发布的v5.4.0版本来说，有MacOS版和Windows版。Linux需要使用其源码来编译安装。

### xelatex

xelatex是将latex转换为pdf的工作，它是texlive的一部份。

在MacOS上，到这里：https://tug.org/mactex/ 进行安装。

对于Debian Linux系统，可以参考这里安装：https://www.tug.org/texlive/debian.html


## 安装
git clone https://github.com/archcra/book-in-md-startup

## 字体
字体在不同的操作系统上，有不同的处理方法。
### MacOS
如在MacOS上，列出字体可以使用如下命令：fc-list

如果只想列出中文字体，可以这样：

fc-list  :lang=zh-cn

### Ubuntu

## 生成PDF
在scripts目录下，执行makeCover.sh以生成封面pdf。然后执行mmd2bok生成完整的PDF。生成的结果会位于当前项目目录下（scripts目录的上一层)。

## 制作内容

### 基本
在原文件上修改即可。

### 增加图片

### 增加章节




