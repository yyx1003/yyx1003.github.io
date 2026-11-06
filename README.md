# yyx1003.github.io

个人主页源码，通过 GitHub Pages 发布。

- 地址：https://yyx1003.github.io
- 纯静态：单文件 `index.html`，无构建步骤、无外部依赖（字体、CSS、JS 全部内置）
- 跟随系统深浅色（`prefers-color-scheme`）
- 自适应移动端

## 本地预览

直接双击 `index.html`，或在目录内执行：

```bash
python -m http.server 8000
```

然后访问 http://localhost:8000

## 修改

| 想改什么 | 位置 |
|---|---|
| 名字、一句话介绍 | `index.html` 的 `<header>` |
| 关于、正在学 | `<main>` 里对应的 `<section>` |
| 项目列表 | `section` 中的 `.card`，复制一份改标题、描述、链接即可 |
| 邮箱 | 搜索 `mailto:`，取消注释并替换 |
| 主题色 | `:root` 里的 `--accent` |
