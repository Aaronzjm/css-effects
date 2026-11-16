# CSS 特效集

个人收藏整理的 **10 个 CSS / SVG 前端特效**，涵盖 3D 变换、描边动画、交互式导航等。所有特效均可**在线预览**（GitHub Pages）。

## 🔗 在线预览

点击下方链接即可在线查看所有特效（无需下载）：

**https://aaronzjm.github.io/css-effects/**

## ✨ 特效列表

| 特效 | 目录 | 技术 |
|------|------|------|
| 🎠 3D 旋转相册 | `effects/3d-rotate/` | CSS 3D Transform |
| ✏️ SVG 描边动画 | `effects/svg-line-animate/` | SVG · Vivus |
| 🦉 猫头鹰登录页 | `effects/owl-login/` | CSS · jQuery |
| 🤖 3D 变形金刚 | `effects/transform-robot/` | CSS 3D · Interactive |
| 📚 侧边导航栏 | `effects/sidebar-nav/` | CSS Transition |
| 🔘 单选按钮动画 | `effects/radio-animate/` | CSS Animation |
| 🧲 导航栏弹性移动 | `effects/nav-elastic/` | CSS Cubic-Bezier |
| 🔽 点击展开按钮 | `effects/expand-btn/` | CSS · JS |
| 🖱️ 鼠标悬停效果 | `effects/hover-effect/` | CSS Hover |
| 📜 滚动加载动画 | `effects/scroll-load/` | Scroll Animation |

## 📁 项目结构

```
css-effects/
├── index.html              # 特效导航首页
├── README.md
└── effects/                # 每个特效独立目录（自包含）
    ├── 3d-rotate/          # 3D 旋转相册
    ├── svg-line-animate/   # SVG 描边动画
    ├── owl-login/          # 猫头鹰登录页
    ├── transform-robot/    # 3D 变形金刚
    ├── sidebar-nav/        # 侧边导航栏
    ├── radio-animate/      # 单选按钮动画
    ├── nav-elastic/        # 导航栏弹性移动
    ├── expand-btn/         # 点击展开按钮
    ├── hover-effect/       # 鼠标悬停效果
    └── scroll-load/        # 滚动加载动画
```

## 🚀 本地运行

这些特效都是**纯静态 HTML**，无需构建：

1. 直接双击任一 `effects/xxx/index.html` 在浏览器打开
2. 或本地起个静态服务器浏览全部：
   ```bash
   # 在项目根目录
   python -m http.server 8000
   # 访问 http://127.0.0.1:8000/
   ```

## 🌐 部署到 GitHub Pages

1. 仓库 Settings → Pages
2. Source 选 `Deploy from a branch`，分支选 `master`，目录选 `/ (root)`
3. 保存后等待几分钟，即可通过 `https://用户名.github.io/css-effects/` 访问

## 📄 许可证

[MIT](LICENSE)
