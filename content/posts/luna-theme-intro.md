---
title: "Luna 主题介绍"
date: 2022-11-17T13:27:26+08:00
categories:
- 教程
tags:
  - hugo
  - 教程
---
Luna 主题是另一个我很喜欢的 hugo 主题，这也是一个很有特色的主题。

{{< github-auto name="Ice-Hazymoon/hugo-theme-luna" >}}

## 开始使用

首先需要安装 hugo-extended、NodeJS，然后再安装 postcss。

```sh
npm install postcss-cli -g
```

然后在博客根目录中执行以下几条命令：

```sh
git submodule add -b master https://github.com/Ice-Hazymoon/hugo-theme-luna themes/hugo-theme-luna
cd themes/hugo-theme-luna
npm install --production
```

项目文档<https://github.com/Ice-Hazymoon/hugo-theme-luna/blob/master/README.zh.md>。

## 特性简介

### 短码

Luna 主题内置了丰富的短码，详情可查看[在线示例](https://hugo-theme-luna.imiku.me/zh-cn/2022/05/02/shortcodes.html/)。

例如轮播图。
{{< carousel "https://picd.zhimg.com/80/v2-e701172c22d4ef63faefd3a3330cee9b_720w.webp?source=1940ef5c" "https://picd.zhimg.com/80/v2-b5133591438589e8fcbf8ef11649d71c_720w.webp?source=1940ef5c" "https://pic1.zhimg.com/80/v2-31e00d19a674edf551f22730a01325be_720w.webp?source=1940ef5c" "https://pica.zhimg.com/80/v2-c4c9bf61c965df98c56e7682aec01739_720w.webp?source=1940ef5c" "https://pic1.zhimg.com/80/v2-723c976e313553f98e5512320aad159b_720w.webp?source=1940ef5c">}}

### 自定义页面

Luna 主题支持归档、Github、友链、搜索、推特等多种自定义页面，参考主题下的样例博客进行配置。
