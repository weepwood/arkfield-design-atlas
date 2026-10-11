# FIELDNOTES — ARKFIELD Graphic Design Atlas

《明日方舟》与《明日方舟：终末地》平面视觉语言研究与互动展示。**独立、非官方、原创示例**，非官方网站镜像。

## 快速使用

直接双击 `index.html`，即可离线运行主要功能。也可用以下命令启动本地 HTTP 服务：

```bash
python -m http.server 8080
# 浏览器访问 http://localhost:8080
```

采用原生 HTML/CSS/JS，没有构建步骤，没有运行时依赖。仅使用本地字体栈，不请求任何第三方脚本、图片或字体服务。

## 功能

- 两款游戏风格一键切换，主题设计令牌实时替换；深浅表面切换
- 风格对比、色彩系统（点击复制 HEX）、字体排版调节
- 三种原创 SVG 海报模板、可修改标题/图形密度/网格/纹理
- 导出可编辑的 SVG 海报（输出结构与网页预览尽量保持一致，字体随本机字体而变化）
- 演示用工业监控面板、档案记录、信号日志；状态按钮可交互
- CSS 扫描/数据脉冲/裁切揭示动效；减少动态效果支持
- 响应式布局，移动侧栏，浏览器本地记忆设置

### 快捷键

- `1` 明日方舟风格 / `2` 终末地风格
- `G` 网格开关 / `M` 动效开关

## 文件

- `index.html` — 页面结构与中文文案
- `styles.css` — 主题、布局、响应式、视觉与动效
- `main.js` — 状态管理、实时演示、海报矢量生成及导出
- `docs/DESIGN_ANALYSIS.md` — 两款游戏风格分析与设计指南

## 版权与来源

本项目为针对公开画面所做的研究、分析与原创视觉演示；不附带官方游戏图标、角色立绘、音乐或游戏内 UI 图片。所列配色为教学近似值，不代表官方品牌规范。官方素材权益归各自权利人所有。

- [明日方舟官方网站](https://ak.hypergryph.com/)
- [明日方舟：终末地官方网站](https://endfield.hypergryph.com/)
- [终末地官网视觉拆解（第三方）](https://yunyueli.github.io/design-teardowns/teardowns/endfield/teardown.html)
- [Arknights Visual Design Skills（第三方）](https://github.com/ganmayou2333/Arknights-Visual-Design-Skills)