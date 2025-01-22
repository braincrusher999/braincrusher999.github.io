---
title: Hexo探索
date: 2025-01-14 20:42:55
tags: [hexo, blog]
---

## 前言

最近想起个个人博客,参考了[小傅哥](https://bugstack.cn/)的[这篇文章](https://www.cnblogs.com/xiaofuge/p/14323626.html),想简单用`Hexo`+`Github Pages`来简单尝试一二.

如此便用Hexo的这次学习路程作为BLOG的开篇之作,也是了了一个难题.

- 安装环境
- 部署到GithubPage
- 配置个性化


## HEXO的安装

整个安装流程实际上在[HEXO官网](https://hexo.io/zh-cn/)上面都有非常详细的文档进行说明,包括HEXO的功能等.在这里就以我自己环境和整个安装部署流程为例,做一个线性叙事.

### 软硬环境

|CPU|内存|操作系统|
|---|---|---|
|AMD Ryzen 7 8845H|32G|Windows 11 24H2 26100.2894|

这个配置对于家用电脑还算比较高,实际上没有太多参考价值.

### 安装步骤

#### 依赖安装

依赖有两个:

- Git
- Node.js

##### Git

Windows上下载`Git Bash`,在[GIT-SCM](https://git-scm.com/)上选择Downloads.再在右边选择Windows即可.我使用的版本是`git version 2.47.1.windows.2`.

下载完成后可以*右键->属性*简单检查一下数字签名,一般是[Johannes Schindelin](https://devblogs.microsoft.com/devops/author/dscho-git/)(不过这个页面有8年没有更新了,仅到`Git for Windows v2.11.0`).

确认没问题之后执行安装包,默认配置安装即可(FIXME:因为我早装了,不记得流程,所以如果有添加到环境变量`PATH`的选项记得添加)

##### Node.js

我使用NVS安装的Node.js

安装NVS的流程如下:

```bash

# 使用winget安装
winget install jasongin.nvs

# 验证
nvs --version

```

我按照的版本是*1.7.1*

按照Node.js的流程如下:

```bash

# 下载指定版本的Node.js
nvs add latest

# 使用指定版本的Node.js
nvs use latest

# 验证node
node -v

# 验证npm
npm -v

```

我安装的版本是:

- Node: v23.6.0
- npm: 10.9.2

> 如果每次启动命令行都需要使用`nvs use`,试试`nvs link`

#### 安装Hexo

这里使用`npm`安装:

```bash

# 安装
npm install -g hexo-cli

# 验证
hexo version

```

Windows环境下应该直接可以输入命令,如果不行可以试试`npx hexo`命令.这里我安装的版本是*hexo: 7.3.0*.

TODO:这里使用官方的NPM源应该无问题.

至此,HEXO的安装工作算是完成了.


## 第一个站点

使用以下命令来创建并初始化一个文件夹作为hexo项目的根目录

```bash

# 创建并初始化

hexo init <folder>
cd <folder>
npm install

```

可以看到目录里还是有点东西的,但这里只挑选几个基础的操作进行介绍

### 修改基础配置

TODO:

### 文章操作

TODO:


## 更换Matery主题皮肤

TODO: