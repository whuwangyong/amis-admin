# amis admin 模板

基于 [amis](https://github.com/baidu/amis) 渲染器，快速搭建自己的管理系统。

## 快速开始

其实这个项目直接双击 `index.html` 都能看大部分效果，不过为了更完整体验，请运行下面的命令：

```bash

# 安装依赖
npm i
# or cnpm i
# or tyarn

# 打开服务
npm start
```

## 部署上线

这个例子中的 amis 等依赖使用外部 cdn，为了稳定请在自己部署的时候将文件下载到本地。

将amis-sdk下载到public/static/目录下即可。

## 参考
mrsdpz的fork项目提供了很多帮助：https://github.com/mrsdpz/amis-admin/blob/master/book/1.md

# 开发记录
1. amis不负责跨域，可以在服务端实现
2. 目前版本header的处理欠妥 https://github.com/baidu/amis/issues/6947