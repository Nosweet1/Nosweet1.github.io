# Nosweet1.github.io

个人主页 —— 纯静态单文件，无构建依赖，直接由 GitHub Pages 托管。

**访问地址**：https://Nosweet1.github.io

## 结构

```
index.html    # 全部内容（内联 CSS，无外部依赖）
.nojekyll     # 跳过 Jekyll 处理，直接发布静态文件
```

## 修改方式

直接编辑 `index.html`，提交后约 30 秒自动生效：

```bash
git add .
git commit -m "update"
git push
```

## 配色

沿用 GitHub 深色主题配色：

| 变量 | 值 | 用途 |
|---|---|---|
| `--bg` | `#0b0e14` | 背景 |
| `--text` | `#e6edf3` | 正文 |
| `--accent` | `#58a6ff` | 强调色 |
| `--accent2` | `#3fb950` | 状态点 |
