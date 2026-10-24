# 霓虹贪吃蛇

一个单文件、零依赖的浏览器小游戏。

## 玩法

- 方向键 / `WASD` 控制移动
- `空格` 暂停 / 继续
- `R` 重新开始
- 手机上滑动屏幕或使用方向按钮

吃掉粉色光点即可得分，撞墙或咬到自己则游戏结束。最高分会保存在浏览器本地。

## 运行

直接双击打开 `index.html`，或在目录中启动任意静态服务器：

```bash
python -m http.server 8000
```

然后访问 <http://localhost:8000>。

## 部署到 GitHub Pages

在仓库的 **Settings → Pages** 中，将来源设为 `Deploy from a branch`，选择 `main` 分支和 `/ (root)` 目录即可。
