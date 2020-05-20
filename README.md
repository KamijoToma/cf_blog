# cf_blog
通过 CloudFlare Workers和Github实现的无服务器博客系统，支持Markdown文章和Markdown评论，程序修改自[kasuganosoras/cloudflare-worker-blog](https://github.com/kasuganosoras/cloudflare-worker-blog)

本仓库内包含博客文章文件存档和已部署的最新版本的Workers源代码

博客文章索引位于`/list.json`，文章文件在`/posts`文件夹，`Workers`源代码在`/CF-Blog.js`

## 特点

* Serverless架构，完全免费，不需要购买任何服务器即可搭建一个基本的博客
* 支持`Markdown`格式的文章和评论，尽情发挥想象力和创造力
* 全站Pjax预加载，响应时间低至1s
* 网页内容完全可定制，你可以任意添加元素和脚本，没有任何限制

## 不足

* 暂未支持`robots.txt`和`sitemap.xml`等爬虫索引功能，可能影响站点收录

##  部署

本程序分为`Workers`和`Valine`两部分，前者负责渲染和展示博客信息，后者负责展示和渲染动态博客评论

### 部署CloudFlare Workers

文档监修中……你可先前往原版仓库地址查找原版部署教程

### 部署Valine评论系统

文档监修中……这部分教程可参考Hexo博客系统部署Valine评论和Valine-Admin评论管理系统的相关教程

## License
`CF-Blog.js`采用MIT License，但要使用此软件，您**有义务**为本项目点击Star按钮。
