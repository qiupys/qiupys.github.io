# qiupys.github.io

邱鹏宇的个人主页（基于 GitHub Pages 的纯静态站点）。

## 本地预览
```bash
cd qiupys.github.io
python3 -m http.server 8000
# 打开 http://localhost:8000
```

## 发布到 GitHub Pages
1. 在 GitHub 创建仓库，名称必须为 `qiupys.github.io`（用户站点仓库命名规范 `<用户名>.github.io`，公开仓库）。
2. 将本目录所有文件推送到该仓库的 `main` 分支。
3. 仓库 Settings → Pages → Build and deployment：
   - Source 选择 `Deploy from a branch`
   - Branch 选择 `main` / `/ (root)`
4. 保存后等待构建（约 1–10 分钟），访问 `https://qiupys.github.io`。

> 目录中的 `.nojekyll` 用于禁用 Jekyll 构建，确保静态文件按原样发布。

## 文件结构
```
qiupys.github.io/
├── index.html        # 站点入口（GitHub Pages 入口文件）
├── .nojekyll         # 禁用 Jekyll
├── README.md
└── assets/photo.jpg  # 个人照片
```
