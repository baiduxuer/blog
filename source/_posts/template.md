title: 我是一个模板
date: 2014-07-14 18:44:12
tags:
- devtool
categories:
- devtool
---
这边是首页展示部分的简介
<!-- more -->

#Markdown语法

>我是引用部分

符号和文本间要有空格

![加载图片](/images/panyan.jpg)

***

*天下武功，唯快不破 天下之事，唯惧用心！*

##Markdown

* 一级分类
    *  还可以加二级分类
    *  还可以加二级分类
* 一级分类 `还可以插入代码`
* 一级分类

###有序列表

1.第一行
2.第二行
3.第三行

###代码

```javascript
  var code = {
    myname  : "leeir",
    site : "http://www.zhuhonglei.com"
  }
```

###我是表格

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

* [*github*](https://github.com/leeir)
* weibo: [*@leeir*](http://weibo.com/leeir)
* [github](https://github.com/leeir)

###NOTE

在用<kbd>hexo deploy</kbd>命令往github推送时，记得将_config.yml中的推送分支改为<kbd>gh-pages</kbd>


```
npm install -g hexo-cli
hexo init blogname
cd blogname
npm install
hexo server -p port
```


###REF
[build-env](http://blog.fens.me/hexo-blog-github/)
[hexo](https://hexo.io/docs/configuration.html)
[theme-next](https://github.com/iissnan/hexo-theme-next)
[markdown](http://segmentfault.com/markdown)