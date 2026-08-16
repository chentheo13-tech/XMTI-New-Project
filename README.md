# XMTI｜GitHub Pages 全新上传包

这是一个已经构建完成的纯静态网站，不包含旧仓库历史，也不需要安装 Node.js 或运行构建命令。

## 使用图形化 Git 客户端发布

1. 在 GitHub Desktop 或其他图形化客户端中选择“添加本地仓库”。
2. 选择整个 `XMTI-New-Project` 文件夹。
3. 点击“发布仓库 / Publish repository”，使用一个新的仓库名称；不要关联原来的旧仓库。
4. 发布完成后，打开新仓库的 **Settings → Pages**。
5. 在 **Build and deployment** 中选择 **Deploy from a branch**。
6. 分支选择 `main`，目录选择 `/ (root)`，然后保存。

等待一两分钟后，网站地址通常为：

`https://你的用户名.github.io/仓库名/`

## 注意

- `index.html`、`assets` 文件夹和所有图片必须一起上传。
- 不要把这个项目关联到原仓库，也不要与原仓库执行 merge；请直接发布为新的远端仓库。
- `.nojekyll` 是 GitHub Pages 所需文件，请保留。
