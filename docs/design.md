# Design — 个人网站设计说明

## 页面区块与浏览顺序
1. **导航栏** — 固定在顶部，包含六个锚点链接
2. **Hero 区** — 首屏显示姓名、照片、定位语和行动按钮
3. **About 区** — 个人简介与数据亮点
4. **Skills 区** — 技能卡片
5. **Experience 区** — 时间线展示四段经历
6. **Projects 区** — 项目展示
7. **Contact 区** — 联系方式

## 颜色方案
- **主色**：紫色渐变（#667eea → #764ba2）
- **背景**：浅灰（#fafafa），区块交叠使用白色
- **文字**：深灰（#333），辅助文字浅灰（#555 / #666）
- **强调**：紫色（#6366f1）

## 字体
系统字体栈：-apple-system, PingFang SC, Microsoft YaHei

## 响应式设计
- 桌面端：双栏 Hero 布局，三列技能网格
- 平板：两列技能网格
- 手机：单列，导航折叠为汉堡菜单

## 文件结构
| 文件 | 职责 |
|------|------|
| index.html | 主页面，全部内容 |
| /assets/css/style.css | 样式 |
| /assets/img/prof_pic.jpg | 个人照片 |
| /assets/img/avatar.svg | SVG 头像备用 |
| docs/prd.md | 产品需求文档 |
| docs/design.md | 本文档 |
| docs/checklist.md | 验收清单 |
| report/final-report.md | 最终报告 |
| screenshots/ | 截图证据 |
