# showstarpro.github.io

Personal homepage of Hanpeng Liu, served at <https://showstarpro.github.io>.

Plain static HTML/CSS, no build step: edit `index.html`, commit to `main`, and GitHub Pages updates the site within a minute or two.

## 更新方法

| 要改什么 | 改哪里 |
|---|---|
| 简介、联系方式、求职说明 | `index.html` 开头的 Intro 部分 |
| 新闻 | `index.html` 的 News 列表，在最上面复制一个 `<li>` |
| 论文 | `index.html` 的 Publications，复制一个 `<li class="pub">`；自己的名字写 `<strong>Hanpeng Liu</strong>` |
| CV | 把 PDF 放到 `assets/Hanpeng_Liu_CV.pdf`，再取消 `index.html` 里 CV 链接那行的注释 |
| 照片 | 替换 `assets/img/photo.jpg`（3:4） |
| 颜色和字体 | `assets/css/site.css` 顶部的 `:root` 变量 |

`index.html` 里标了 `TODO` 的注释是还要补全的论文信息。

字体用的是自托管的 IBM Plex（SIL Open Font License，见 `assets/fonts/OFL.txt`），没有依赖 Google Fonts，国内也能正常打开。
