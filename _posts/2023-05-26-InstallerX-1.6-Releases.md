---
layout:       post
title:        "InstallerX stable v1.6 发布"
author:       "Rosan(Maker), RinCynar(Repost)"
header-style: text
catalog:      true
tags:
  - InstallerX
---
## InstallerX 1.6 正式版发布, [下载该版本](/file/InstallerX-stable-v1.6.apk).
### 更新内容
#### 新增 授权复用
#### 一定时间内的不会重复申请授权，对多个安装有一定提速效果
#### 新增 上一步按钮占用空间压缩
#### 新增 ROOT授权失败提示
#### 新增 自定义授权器授权失败提示
#### 新增 ROOT授权与自定义授权更换到新的实现方式
#### 修复 Dhizuku授权时的锁定安装器功能
#### 先用Shizuku授权锁定，再用Dhizuku授权锁定，目前效果与ROOT授权锁定等同。
#### 如果依然锁定失败，请使用Xposed模块实现的锁定器。
#### 修复 Shizuku授权时的自动删除安装包功能
#### 修复 部分安装包图标不显示的问题
#### 修复 KernelSU部分情况无法授权的问题
#### 删除 主页设备信息卡片
