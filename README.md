# AI 博士生个人主页

这是一个可以直接部署到 GitHub Pages 的静态学术个人主页，适合人工智能方向博士生展示个人简介、研究方向、论文、项目和经历。

## 本地预览

直接双击 `index.html`，或运行本地静态服务器预览：

```bash
python -m http.server 8000 --bind 127.0.0.1
```

然后打开 `http://127.0.0.1:8000/`。

## 修改内容

优先替换 `index.html` 里的这些位置：

- `Your Name`
- `Your Lab / University`
- `mailto:yourname@example.com`
- `https://github.com/yourname`
- `Google Scholar`、`CV` 链接
- About、News、Selected Publications、Projects、Education & Experience 里的占位内容

头像使用项目根目录的 `personal.jpg`。

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
