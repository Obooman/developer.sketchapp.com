# sketch-dev.com

本网站是[Sketch](http://sketchapp.com)开发的解释页面的中文版本, 托付在 [sketch-dev.com](http://sketch-dev.com)上。

本项目基于 [Jekyll](http://jekyllrb.com)。

## 安装

在本地搭建此项目, 你需要安装 [node](https://nodejs.org/en/) 和 [bundler](http://bundler.io). Once you have them, run this:

```
npm install --global gulp
bundle install --path _vendor
npm install
```

然后运行

```
gulp
```

来启动服务器并打开页面.

Note: 你在运行`bundle install`的说可能会碰到nokogiri的bug，解决方案请参照 [Nokogiri's page](http://www.nokogiri.org/tutorials/installing_nokogiri.html#mac_os_x)
