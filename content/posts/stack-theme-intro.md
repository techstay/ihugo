---
title: "Stack 主题介绍"
date: 2022-11-15T12:44:50+08:00
image: https://user-images.githubusercontent.com/5889006/190859441-141b5f81-8483-40d2-bd96-ebf85616a46d.png
categories: 教程
tags:
  - hugo
  - 教程
---
[hugo-theme-stack](https://github.com/CaiJimmy/hugo-theme-stack)是一个优雅的 hugo 博客主题，界面美观好看，目前在 github 上有两千七百赞。本文简单介绍一下 stack 主题的一些特性。如果需要详细文档，参考[官方文档](https://stack.jimmycai.com/)。

## 开始使用

安装主题。

```sh
git submodule add https://github.com/CaiJimmy/hugo-theme-stack themes/hugo-theme-stack
```

将主题文件夹`exampleSite`里的`config.yaml`和`content`中的各页面文件复制到博客中对应位置，再按需求修改就好了。

## 特性简介

### 题图

stack 主题支持在每个页面上添加预览图，只要在页面的 FrontMatter 上添加`image`属性和图片 URL 即可。

```yaml
---
title: "Stack 主题介绍"
date: 2022-11-15T12:44:50+08:00
image: https://user-images.githubusercontent.com/5889006/190859441-141b5f81-8483-40d2-bd96-ebf85616a46d.png
categories: 教程
tags:
  - hugo
  - 教程
---
```

### 短码

短码是一些特定 HTML 代码的包装，可以给页面添加更多丰富的内容。stack 主题支持 B 站视频、腾讯视频等多种短码，详情可以在[这里](https://stack.jimmycai.com/writing/shortcodes)查看。

{{< bilibili BV1Ut411D7rY >}}

### 自定义header/footer

stack 主题提供了两个保留文件，可以用来添加额外的样式和 JS 脚本。例如这里添加的`canvas-nest`网页背景特效。

- `layouts/partials/head/custom.html`
- `layouts/partials/footer/custom.html`
