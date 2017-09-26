文档生成工具整理
---

## cli  ##

### gitbook ###

[gitbook](https://www.gitbook.com/)网站上有很多优优质的电子书。

```
$ npm install -g gitbook-cli
$ mkdir do/gitbook && cd do/gitbook
$ gitbook init
$ npm run dev
# 安装插件
$ gitbook install ./
```

### [docute](https://docute.js.org/#/zh-Hans/) ###
> docute 让你直接写 markdown 文件作为文档来显示而不需要编译成 html 这一步，你的文档目录里只需要一个首页 index.html 和你的配置文件 config.js。docute 会直接渲染这些 markdown 文件为一个单页应用。

### [docsify](https://github.com/qingwei-li/docsify) ###
> docsify 是一个动态生成文档网站的工具。不同于 GitBook、Hexo 的地方是它不会生成将 .md 转成 .html 文件，所有转换工作都是在运行时进行。

- [参考文档](https://toolchain.gitbook.com/setup.html)
- [GitBook 插件](https://gitbook.zhangjikai.com/plugins.html)
- [官方插件GitBook Plugins](https://plugins.gitbook.com/)


## api文档 ##

### [apiDocjs](http://apidocjs.com/) ###


## 其他 ##

### [mdwiki](https://github.com/Dynalon/mdwiki) ###

> CMS/Wiki system using Javascript for 100% client side single page application using Markdown.

只需要引入一个`html`根据路径自动加载`.md`文件。最后更新是2014年，不推荐使用。