# 生命探索者：史前滨海沼泽

可直接游玩的 Three.js 网页场景。项目包含网页代码、地形与植物模型，以及本地 Three.js 运行库。

## 运行

需要安装 Python 3。进入项目目录后运行：

```bash
python3 -m http.server 8000
```

然后在浏览器打开 <http://localhost:8000/>。请通过本地 HTTP 服务运行，直接双击 `index.html` 会导致模块和模型加载失败。

## 操作

- 点击“开始探索”进入场景
- `W` `A` `S` `D` 移动，鼠标转动视角
- `Shift` 加速，`Esc` 释放鼠标
- 使用页面上的重置按钮回到出生点

## 许可

本项目代码和随附场景模型以 MIT License 许可，可下载、使用、修改和再发布。推送到 `main` 后，GitHub Actions 会自动发布可游玩的 GitHub Pages 页面；首次发布可在仓库的 Actions 页面查看部署结果。`vendor/` 中的 Three.js 文件保留其原有版权声明和 MIT 许可，详见 `vendor/LICENSE`。
