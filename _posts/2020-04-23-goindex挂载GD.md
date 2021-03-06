---
date: 2020-04-23 20:26:40
layout: post
title: Goindex挂载GD
subtitle: GD goindex
description: GoogleDrive GoIndex部署教程
image: https://p3terximg.gitee.io/post/20191107212146.jpg
optimized_image: https://p3terximg.gitee.io/post/20191107212146.jpg
category: movies
tags:
  - web
  - goindex
  - gdrive
author: deilt
---
# 团队盘 Teamdrive
没有Google Drive团队盘的小伙伴可以自助添加

1. 英国谢菲尔德大学：https://gdrive.zppcw.cn/

2. 404 NOT FOUND：https://gd.404edu.workers.dev/

3. https://gd.zxd.workers.dev/

4. http://leon.educationhost.cloud/

5. swccd.edu团队盘：https://teamdrive.xcpx.workers.dev/

5. 洛杉矶加利福尼亚大学团队盘：https://ucla.ur.workers.dev/

6. 日本国際大学团队盘：https://iuj.ur.workers.dev/

7. 自动创建：https://www.teamdrive.workers.dev

感谢大佬提供的Google Drive团队盘

# GoogleDrive GoIndex部署教程

goindex作者[@donwa](https://github.com/donwa)

[Github源码地址](https://github.com/donwa/goindex)

# Demo 

<https://index.deilt.workers.dev/>

<https://index.rouis.workers.dev/>
# Goindex 概述 

Google Drive Directory Index
Combining the power of [Cloudflare Workers](https://workers.cloudflare.com/) and [Google Drive](https://www.google.com/drive/) will allow you to index you files on the browser on Cloudflare Workers.

# Deployment
1.Install **rclone** software locally

2.Follow <https://rclone.org/drive/> bind a drive

3.Execute the command **rclone config file** to find the file **rclone.conf** path

4.Open **rclone.conf**,find the configuration **root_folder_id** and **refresh_token**

5.Download index.js in <https://github.com/donwa/goindex> and fill in root and refresh_token

6.Deploy the code to [Cloudflare Workers](https://workers.cloudflare.com/)

# Quick Deployment
1.Open <https://installen.gd.workers.dev/>

2.Auth and get the code

3.Deploy the code to [Cloudflare Workers](https://workers.cloudflare.com/)

# 不同版本选择

## 简洁原版 
![](https://index.deilt.workers.dev/0:/blog/blog-pic/3.jpg)

## 魔改多盘 支持搜索 
![](https://index.deilt.workers.dev/0:/blog/blog-pic/1.jpg)

### 源码
点击[下载](https://index.deilt.workers.dev/0:/blog/source-code/goindex%E5%A4%9A%E7%9B%98%E9%AD%94%E6%94%B9%E7%AE%80%E4%BB%8B%E7%95%8C%E9%9D%A2.js)

## 魔改单盘 支持搜索 界面美观
![](https://index.deilt.workers.dev/0:/blog/blog-pic/2.jpg)

![](https://index.deilt.workers.dev/0:/blog/blog-pic/4.jpg)

### 源码
点击[下载](https://index.deilt.workers.dev/0:/blog/source-code/goindex%E5%8D%95%E7%9B%98%E9%AD%94%E6%94%B9%E6%BA%90%E7%A0%81.js)