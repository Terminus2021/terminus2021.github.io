---
layout: post
title:  【精】如何协助参与Terminus计划
date:   2021-11-14
categories: sticky
tags: 精品
description: 修改自《如何协助参与端点星计划》
is_sticky: true
---

## Terminus是什么

Terminus 是在 GitHub 开放平台搭建的一个站点，用于广集各界有才之人在此撰写各类文章。
2021年11月发起，以科技、新闻类文章为主。

## 抵抗资本霸权，需要公众参与新方法

在严重依赖主机商的情况下，博客写手抵抗资本霸权，保证文章传播阅读的持久有效性，现在比较常见的方法有：

- 自开GitHub Pages
- 微信公众号
- 博客园
- 评论区写小作文得了

可以发现，这些写作方法并没有很好地使用超链接、微信之外的网站平台，它们有时候也会意想不到的消失，就像断断续续的水滴。

博客写手参与抵抗主机商博客的霸权，需要开辟新的方法，重新捡起超链接、网站，再加上开源开放的协作平台。

Terminus正是出于这样的原因与目的而产生。

## 如何参与Terminus

### 需要的基本技能

- 熟悉使用 Markdown 基本标记语法
- 熟悉 Markdown 文本编辑器（可选项）：这些工具适用于对 Markdown 语法不熟悉的协作者
  - [MarkdownPad](http://markdownpad.com/)
  - [Atom](https://atom.io/)
  - html 转成 markdown：浏览器插件「[简悦](http://ksria.com/simpread/)」
- 熟悉 GitHub 平台使用

### PR 步骤说明

1. 注册并登录 [GitHub](https://github.com/) 帐号

2. fork Terminus 仓库到自己的 GitHub: 访问[Terminus2021](https://github.com/Terminus2021/terminus2021.github.io) GitHub页面，点击右上角 **Fork** 按钮。

3. 编辑文章：在自己帐号里面的 terminus2021.github.io 仓库，编辑添加备份的文章。

    - 第一种方式：直接在线编辑添加
      1. 点击进入 `_posts/` 文件夹，点击上面的 **Create New File**
      2. 命名文章标题：统一格式为「Year-Month-Day-title.md」，例如 `2018-01-01-biao-ti.md`
      3. 在下方 **Edit new file** 空白区域编辑内容，编辑格式看下方[备份格式编辑要求](#备份格式编辑要求)
      4. 点击 **Preview** 可预览效果
        ![add_new_post.png](https://i.loli.net/2020/02/09/uhZUAWm6yr3MJ4I.png)

    - 第二种方式：从本地上传已编辑的 md 文档
      1. 点击进入 `_posts/` 文件夹，点击 **Upload files**
        ![drag_files.png](https://i.loli.net/2020/02/09/Be21nogCdw4pJlE.png)
      2. 从本地选择要上传的 md 文档

5. 填写 **commit new file**
  ![commit_new_file.png](https://i.loli.net/2020/02/09/fCs72X3pBYgSkT8.png)

6. 向原仓库提交 PR
    
    在自己的仓库页面，点击 **new pull request**，再点击 **create pull request**，填写 PR 描述并提交。
    ![new_pull_request.png](https://i.loli.net/2020/02/09/mONEWGFJwXod1ep.png)

7. 等待 Terminus2021 查看 PR ，符合要求的内容会 merge(合并）。

### 备份格式编辑要求

1. 头部格式：

    ```
    ---
    layout: post
    title:  Lorem Ipsum Dolor sit Amet
    date:   2018-04-09
    categories: Archive
    tags: Lorem
    image_feature: ""
    description: Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
    ---
    ```
    - layout: post 保持不变
    - title: 用备份文章的标题
    - date: 日期
    - categories: Archive 保持不变
    - tags: 标签（在Terminus2021查看是否已有相关标签）
    - image_feature: "如果文章有合适的图片可作为封面图，图片链接填在这里，若无则不填写"
    - description: 可用文章的导语做简述

2. 来源说明格式

    ```
    ---
    （如果你曾在别的平台写作或转载）原文来自公号名称/网站名称：~~[文章标题](原文链接)~~
    
    作者：XXX
    ---
    ```

3. 正文小标题，使用 h2 或 h3。

4. 图片编辑
  1. 使用本站提供的图片仓库（https://github.com/Terminus2021/photos）生成链接（格式为：https://terminus2021.github.io/photos/name.png）。
  2. 图注用 `<center>图注</center>` 居中。
    ```
    ---
    
    作者：Terminus2021
    ---
    ```

