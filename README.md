# Modular Intelligence Robot Visualizer

一个零依赖、纯静态的模块化机器人产品构想可视化界面。

## 当前内容

- 四阶段产品路线：工具快换、整臂迁移、无人机操作、模块化人形
- 机器人头部、肩、肘、腕、手指、腿部与接口关节细节
- 动态时间线、播放/暂停、阶段切换
- 难点图标与画面时间码、坐标圈选联动
- 三层智能体架构与统一接口说明
- 响应式布局与明暗主题

## 本地打开

最简单的方式：直接双击 `index.html`。

也可以启动本地静态服务器：

```bash
python3 -m http.server 8080
```

然后打开 `http://localhost:8080`。

## GitHub Pages

仓库中包含 `.github/workflows/pages.yml`。首次使用时，在仓库：

`Settings → Pages → Build and deployment → Source → GitHub Actions`

保存后重新运行 Pages workflow。

## Codex 迭代

见 `CODEX_PROMPT.md`。建议按任务拆分提交，不要一次重写全部界面。
