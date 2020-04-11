博客使用`hugo`构建，主题为`Even`。

生成新的文章草稿：
hugo new post/first-post.md

生成静态文件：
hugo --theme=even --baseUrl="https://amesy.me/" -d public

本地调试：
hugo server -d public

提交代码：
cd public
git ...
