# 三叶草的仲夏

仲夏的三叶草，纯洁而独特，它们不需要繁华，只需在草原上自由绽放。

## Get started
- 安装hugo: https://gohugo.io/installation/
- hugo教程：https://gohugo.io/getting-started/
- 主题模板：https://github.com/CaiJimmy/hugo-theme-stack-starter

## Add content
- 添加一个新页面，页面路径：`content/post/my-first-post.md`

```shell
hugo new content post/my-first-post.md
```
>注意：此时文件还是草稿状态，最终部署时不会发布到站点，需要将文件头内容`draft: true`改为false

- 本地调试查看

```shell
hugo server -D
```

- 构建生成，将在项目根路径生成`public`目录
```shell
hugo
```