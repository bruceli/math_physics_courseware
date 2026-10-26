# 数理自学课件

交互式 HTML 自学课件，纯静态，无需构建，部署在 Vercel。

```
index.html                    课程目录
analysis/01-limits/index.html 数学分析 第一章 极限：ε-N 与 ε-δ
vercel.json                   Vercel 配置
```

新增章节：在对应课程目录下建 `NN-slug/index.html`，并在根目录 `index.html` 里加一行链接。推送到 `main` 后 Vercel 自动部署。
