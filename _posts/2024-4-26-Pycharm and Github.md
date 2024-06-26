---
title: Pycharm and Github
author: Liu
date: 2024-04-26 16:10:00 +0800
categories: [HOW to USE IT, Python]
render_with_liquid: false
img_path: https://raw.githubusercontent.com/IsKevinLiu/IsKevinLiu.github.io/main/_image/20240426/
---


# 安装与前期准备
## 软件安装
1. 安装 Python
   安装地址: [Download](https://www.python.org/downloads)
   > 安装时勾选添加环境变量'Add Python.exe to PATH', 避免需要手动写入
   {: .prompt-info }
2. 安装 Pycharm (Python IDE)
   安装地址: [Download](https://www.jetbrains.com/pycharm/download/?section=windows)
3. 安装 Anaconda (Python Environment)
   安装地址: [Download](https://www.anaconda.com/products/individual)
4. 安装 Git  (Code Version Control)
   安装地址: [Download](https://git-scm.com/downloads)

## 从Github中克隆项目
1. 在GitHub中选择需要克隆的仓库并复制仓库地址.
   ![Github](002.png)
2. Pycharm中创建一个新的项目.
3. 打开`主菜单-文件-设置`(Ctrl+Alt+S), 在版本控制中找到`git`. 点击测试自动检测git路径或者将自定义安装路径手动输入.
   ![Settings git in Pycharm](001.png)
4. 打开`主菜单-VCS`选择`创建git仓库...`.
5. 打开`主菜单-VCS`(or `主菜单-git`)选择`克隆...`在URL中输入项目地址, 选择本地路径, 点击`Clone`.
  
