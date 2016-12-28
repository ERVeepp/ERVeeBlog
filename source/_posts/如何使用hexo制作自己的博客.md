---
title: 如何使用hexo制作自己的博客
---
## 一：node环境的安装

首先当然是安装node环境了，找到node官网，下载最新的node环境

建立一个空的文件夹，可以叫blog

然后运行如下命令：

* npm install -save
* npm install -g hexo
* npm install hexo-deployer-git --save

## 二：安装一些其他的需要的包

* npm install --save
hexo-renderer-jade
hexo-generator-feed
hexo-generator-sitemap
hexo-browsersync
hexo-generator-archive

### 三：常用的一些操作

* hexo init 初始化
* hexo g 生成静态文件
* hexo s 启动服务，浏览器输入http://localhost:4000
* hexo d 上传到github上，前提是_config.yml文件配置恰当

### 四：写在后面

* apollo主题和Vue的官网有点像，所以...你懂的，这里是主题地址: [apollo](https://github.com/ERVeepp/hexo-theme-apollo)
