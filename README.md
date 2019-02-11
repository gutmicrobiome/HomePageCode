##### 开发环境

Powered by Hexo v3.8.0 | Theme – hiker



### 几个基本操作

**几个常用命令**

`hexo g` 生成静态网页

`hexo d` 部署网页到gitpage

`hexo s`开启网页的本地服务 

`git add .` 把所有新文档添加的暂存区

`git commit -m 'message'`把暂存区内容存档，message为该版本你需要记录的说明

`git push `  把本地的项目，推送到远程仓库(github)

**替换主页图片**

在`themes/hiker/source/css/images`，下添加图片，在`themes/hiker/_config.yml`中，`home_background_image`，添加相应的图片链接。

![](https://github.com/LHEISSR/markdownphoto/blob/master/20190211_1.png?raw=true)



**Home页文档编辑**

Home 页内容有多篇markdown文档构成，文档简历时间越近，排列在越前面。

`hexo new post <title>` ，文章会存储在`source/_posts`。例如`hexo new post aaa`，新建一篇名为aaa的文章

备注：Home中的makedown文档图片引用，器务必使用网络地址的格式。

**Research、People、Publications、 Lab-activities、Useful-Links、Contact页编辑**

此类页面由一篇makedown文档构成。makedown文档的在`source/xxxx/index.md`。编辑相应的markdown文档即可修改相应的页面内容。

备注：此处makedown图片应用尽量使用网络地址的格式，也可使用相对地址。

