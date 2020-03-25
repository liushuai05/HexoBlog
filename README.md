![build-info](https://travis-ci.org/erguotou520/HexoBlog.svg)
[![Netlify Status](https://api.netlify.com/api/v1/badges/51b3b9d2-581b-429f-bd2e-4b9f3da7c4c0/deploy-status)](https://app.netlify.com/sites/elastic-shockley-940ec0/deploys)
#### 安装:
如果报以下错误
```shell
INFO  Checking dependencies
ERROR Package cheerio is not installed.
ERROR Package hexo-pagination is not installed.
ERROR Package hexo-generator-archive is not installed.
ERROR Package hexo-generator-category is not installed.
ERROR Package hexo-generator-index is not installed.
ERROR Package hexo-generator-tag is not installed.
ERROR Package hexo-renderer-ejs is not installed.
ERROR Package hexo-renderer-markdown-it is not installed.
ERROR Package hexo-renderer-stylus is not installed.
ERROR Please install the missing dependencies from the root directory of your Hexo site.
```
执行下命令安装依赖插件即可解决
```shell
npm install hexo-pagination
```

#### 命令:
```shell
#安装
npm install
#编译(生成静态文件)
hexo generate
#开启服务
hexo server
#部署网站
hexo deploy

```

更多命令参见hexo指令说明[点击访问](https://hexo.io/zh-cn/docs/commands)
#### 在线演示
[点击访问博客](https://blog.erguotou.me)
#### 鸣谢
[hexo-theme-icarus](https://github.com/ppoffice/hexo-theme-icarus.git)
[erguotou520](https://github.com/erguotou520/HexoBlog.git)

