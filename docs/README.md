# ZBlogPHP-Wiki

ZBlogPHP非官方Wiki

协作参与：[https://github.com/wdssmq/ZBlogPHP-Wiki](https://github.com/wdssmq/ZBlogPHP-Wiki "wdssmq/ZBlogPHP-Wiki: ZBlogPHP非官方Wiki")

更新时间： {docsify-updated}

## 关于docsify

官网：[docsify](https://docsify.js.org/#/zh-cn/ "docsify") ← 已经指向中文说明

基本的命令备忘：

```bash
# npm i docsify-cli -g
cnpm i docsify-cli -g

# cd "/d/web/#Git/ZBlogPHP-Wiki"
docsify init ./docs

# cd "/d/web/#Git/ZBlogPHP-Wiki"
docsify serve docs
# Listening at
# http://localhost:3000

```

## docsify使用技巧

### 嵌套调用重复内容

将需要重复使用的内容单独写进一个*.md文件，然后可以用如下语法引用：

```md
[host](terms/host.md ':include')

[path](terms/path.md ':include')
```

效果如下：

[host](terms/host.md ':include')

[path](terms/path.md ':include')


