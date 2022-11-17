# ihugo

一个没啥用的 hugo 项目，演示我喜欢的一些 hugo 主题。在线访问：

- [hugo-theme-stack 主题](https://ihugo-stack.techstay.tech)
- [hugo-theme-luna 主题](https://ihugo-luna.techstay.tech)

## 快速开始

### 安装 hugo

```sh
scoop install hugo-extended
```

### 新建博客

```sh
hugo new site <dirname>
```

### 新建文章

切换到新生成的博客文件夹中，再执行：

```sh
hugo new post <filename>
```

### 本地访问

```sh
hugo server -D
```

或者为了省事也可以自己建个脚本，将内容放进去，下次就可以直接用脚本`dev.ps1`来调用命令了。

## 主题

hugo 有大量社区主题，可以挑自己喜欢的去用。每个主题配置方法不同，请到各自的主题项目主页去查看配置方法。一般来说，主题都会提供一个示例网站，将示例网站里的配置文件和样式文件复制到自己项目中，然后修改为自己的样子就可以了。

## hugo-theme-stack

这是我现在正在用的主题，两千七百赞，强烈推荐。

- 主题地址 <https://github.com/CaiJimmy/hugo-theme-stack>
- 在线演示 <https://demo.stack.jimmycai.com>

安装主题。

```sh
git submodule add https://github.com/CaiJimmy/hugo-theme-stack themes/hugo-theme-stack
```

将主题文件夹`exampleSite`里的`config.yaml`和`content`中的各页面文件复制到博客中对应位置，再按需求修改就好了。

### hugo-theme-luna

这个主题我很喜欢，[作者的博客](https://imiku.me)也蛮有意思的。

- 主题地址 <https://github.com/Ice-Hazymoon/hugo-theme-luna>
- 在线示例 <https://hugo-theme-luna.imiku.me>

安装前需要先安装`postcss`。

```sh
npm install postcss-cli -g
```

然后用 submodule 方式安装主题。

```sh
git submodule add -b master https://github.com/Ice-Hazymoon/hugo-theme-luna themes/hugo-theme-luna
cd themes/hugo-theme-luna
npm install --production
```

然后将主题里面的`config.yaml`复制一份出来，在此基础上修改配置。
