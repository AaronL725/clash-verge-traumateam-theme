# 贡献指南

感谢你愿意改进 Trauma Team Liquid Glass。

## 提交问题

请尽量提供：

- Clash Verge Rev 版本。
- 操作系统及版本。
- 发生问题的具体页面。
- 可复现步骤。
- 截图或录屏。
- 是否启用了“减少透明度”或“减少动态效果”。

## CSS 修改原则

- 优先使用 Clash Verge Rev 的语义类和 MUI 公开组件类。
- 避免 `.css-xxxxxx` 等构建哈希类名。
- 避免远程图片、远程字体、`@import` 和 JavaScript。
- 避免对 `*`、所有 `div` 或所有 `.MuiPaper-root` 进行无差别覆盖。
- 新增透明材质时注意 GPU 开销和辅助功能回退。
- 修改后至少检查 Home、Profiles、Proxies、Connections、Rules、Test 和 Settings。

## Pull Request

请在 PR 中说明：

- 修改目的。
- 涉及页面。
- 修改前后截图。
- 已测试的 Clash Verge Rev 与系统版本。
