# ldd-blog

赖东东的个人博客，使用 hugo 搭建，even 主题

[主页](https://blog.abigballoon.top/)

## 项目结构

```
.
├── archetypes  // 原型模版
├── content  // 站点内容，每个目录作为一个section
├── data  // 存放数据 .json .yaml .toml，可以创建动态内容
├── layouts  // html模版，设置站点布局
├── static  // 静态文件 css js image
├── themes  // 主题
└── config.toml  // 配置
```

## Develop

[安装Hugo](https://gohugo.io/getting-started/installing)

```bash
# 新建文章，文章只能在post下，可以在post下建子目录
hugo new post/article.md

# 默认启动http://localhost:1313/
hugo server

```

## Deploy

push到main分支后，GitHub Actions将自动部署

## TODO

- [x] 添加侧边栏：分类列表、标签列表、最新 n 篇文章、相关 n 篇文章
- [ ] 固定侧边栏
- [ ] 全局搜索
