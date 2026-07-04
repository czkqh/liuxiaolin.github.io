# 个人主页

这是一个可以直接部署到 GitHub Pages 的静态个人主页。

## 本地预览

直接双击 `index.html`，或在浏览器里打开这个文件即可预览。

## 修改内容

优先替换这些位置：

- `index.html` 里的 `你的名字`
- `mailto:yourname@example.com`
- `https://github.com/yourname`
- `https://www.linkedin.com/in/yourname`
- “关于我”“精选项目”“经历”里的占位文案

## 发布到 username.github.io

1. 在 GitHub 新建一个仓库，名字必须是 `你的GitHub用户名.github.io`。
2. 把本目录里的文件提交并推送到那个仓库。
3. 打开 `https://你的GitHub用户名.github.io`，通常几分钟内就能看到页面。

常用命令：

```bash
git init
git add .
git commit -m "Create personal homepage"
git branch -M main
git remote add origin https://github.com/你的GitHub用户名/你的GitHub用户名.github.io.git
git push -u origin main
```

如果你用的是普通仓库名，也可以在仓库的 Settings -> Pages 里选择从 `main` 分支部署。
