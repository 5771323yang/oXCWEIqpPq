# 警员信息管理系统 python637

## 项目概述

警员信息管理系统是一款基于Python3.6.5、pyqt5和MySQL开发的管理软件，主要针对警员信息进行维护和管理，包括登录验证、个人信息维护、部门信息管理以及警员信息管理等模块。

## 技术栈

- Python3.6.5
- PyQt5
- MySQL

## 功能模块

### 1. 登录

系统提供管理员和普通用户两种登录角色：

- 管理员：使用`admin`账户登录

### 2. 个人信息维护

普通用户可登录系统修改个人信息。

### 3. 部门信息管理

管理员专有功能，包含部门信息的增删改查操作。

### 4. 警员信息管理

管理员可以进行警员信息的增删改查，其中警号作为唯一标识。

### 5. 警员部门信息管理

管理员可进行部门与警员信息的关联操作，支持数据增删查，并提供下拉框模糊搜索功能。

## 系统角色

- 管理员：负责系统维护和所有数据的增删改查操作。
- 普通用户：仅能登录并修改个人信息。

## 运行环境

- 操作系统：兼容Windows、Linux和Mac OS
- Python版本：3.6.5及以上
- 数据库：MySQL

## 部署步骤

1. 安装Python3.6.5环境
2. 安装PyQt5库
3. 安装MySQL数据库，创建相应数据库和表
4. 导入提供的SQL脚本
5. 部署源代码，运行系统

## 目录结构

```
project/
├── main.py # 主程序
├── forms/ # 界面相关
│   └── main_window.ui
├── models/ # 数据模型
│   └── user_model.py
├── views/ # 视图逻辑
│   └── main_view.py
└── controllers/ # 控制器逻辑
    └── main_controller.py
```

## 核心亮点

- 基于Python和PyQt5，界面友好，操作简便。
- 警号唯一性检查，保证数据的准确性。
- 提供模糊搜索功能，提升信息检索效率。
- 角色权限分离，保障系统安全性。

## 免费源码获取

```
8000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img13.360buyimg.com/ddimg/jfs/t1/346387/37/7140/29625/68d4f337Fe289bec0/e4947b7a976feedc.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/346859/24/7141/34331/68d4f337F0b9e3377/6cff2cd8727242f3.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/333442/34/17083/72406/68d4f338F2fcce52a/364eab9c882e4d48.jpg)

![](https://img12.360buyimg.com/ddimg/jfs/t1/325019/5/23900/74009/68d4f338F92cedc96/20581f359fdfeb96.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/336716/23/14524/62569/68d4f338F353f2f10/3ea65aee27c701c4.jpg)
