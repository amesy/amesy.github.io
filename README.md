### 说明

博客使用`hugo`构建，主题为`Even`。

### 步骤

生成新的文章草稿：
```shell
hugo new post/first-post.md
```
生成静态文件：
```shell
hugo --theme=even --baseUrl="https://amesy.me/" -d public
```
本地调试：
```shell
hugo server -d public
```
提交代码：
```shell
cd public
git add .
git commit -m "update file"
git push -u origin master
```
