# 5E 不全书 · 3D 书架

把 [5E 不全书](https://5echm.kagangtuya.top/) 的 77 本资源做成一面可旋转、可点开的 CSS 3D 书架。

- 77 本，6 个分类：核心、传承、规则、设定、伙伴、其他
- 纯 CSS 3D 立方体 + 原生 JS，无 WebGL、无框架
- 封面与书脊为 AI 生成的复古印刷风格图片
- 点击书脊滑到中间，点击封面打开详情卡
- 支持滚轮、拖拽、方向键、分类标签、移动端和减少动效

在线页面：https://2zh.github.io/5e-bookshelf/

## 本地运行

```bash
python3 -m http.server 8000
# 打开 http://localhost:8000
```

## 结构

```
index.html      页面
covers/         77 张封面（2:3）
spines/         77 张书脊（1:7.75 窄条）
textures/       纸张纹理
```
