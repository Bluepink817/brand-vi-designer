# Brand VI Designer

一个面向品牌视觉识别（VI）项目的 AI Skill。

它把“品牌分析 → 视觉方向 → LOGO规范 → 色彩 → 字体 → 辅助图形 → 应用 → 质量检查”封装成可重复调用的工作流，适合用来完成品牌提案、VI系统、商业应用与视觉一致性检查。

## 能做什么

- 品牌 / 行业 / 用户分析
- 品牌视觉关键词提炼
- Visual Direction
- LOGO标准制图与使用规范
- 品牌色彩系统
- 中英文字体与层级建议
- 辅助图形开发逻辑
- 摄影与版式方向
- 办公应用
- 员工服装
- 包装方向
- 广告应用
- 社交媒体应用
- VI一致性检查

## 推荐输入

你可以提供：

- 品牌名称
- 行业
- LOGO
- 产品图片
- 品牌定位
- 目标用户
- 参考案例
- 想要的风格
- 输出尺寸 / 比例 / 数量

例如：

> 使用 Brand VI Designer。根据我上传的咖啡品牌 Logo，为品牌建立一套年轻、城市、温暖、极简的 VI 系统，并完成行业背景、市场分析、标准制图、色彩规范、办公应用、广告应用 6 个版面。每张 16:9 单独输出。

## 默认六页结构

1. Industry Background / 行业背景
2. Market Analysis / 市场分析
3. Logo Construction / 标准制图
4. Color System / 色彩规范
5. Office Applications / 办公应用
6. Advertising Applications / 广告应用

## 文件结构

```text
brand-vi-designer/
├── SKILL.md
├── README.md
├── LICENSE.md
├── agents/
│   └── openai.yaml
├── references/
│   ├── 01-brand-analysis.md
│   ├── 02-visual-direction.md
│   ├── 03-logo-system.md
│   ├── 04-color-system.md
│   ├── 05-typography-system.md
│   ├── 06-graphic-photography-layout.md
│   ├── 07-applications.md
│   ├── 08-image-generation.md
│   └── 09-quality-control.md
└── assets/
    └── examples/
        └── README.md
```

## 本地安装（Codex）

将整个 `brand-vi-designer` 文件夹放入：

```text
$HOME/.agents/skills/
```

最终应类似：

```text
$HOME/.agents/skills/brand-vi-designer/SKILL.md
```

Codex 通常会自动检测技能变化；如果未出现，重启 Codex。

也可以使用 Codex 的 `$skill-installer` 从公开 Git 仓库安装。

## 使用

- ChatGPT 桌面端：可在支持 Skills 的位置通过 `@` 选择技能。
- Codex CLI / IDE：可以通过 `/skills` 查看，或使用 `$` 提及技能。
- 当用户请求与 `description` 高度匹配时，宿主也可以隐式触发该 Skill。

## 案例图片

把你自己的真实案例放入：

```text
assets/examples/
```

建议每个品牌一个文件夹，例如：

```text
assets/examples/coffee-brand/
01-industry-background.jpg
02-market-analysis.jpg
03-logo-construction.jpg
04-color-system.jpg
05-office-applications.jpg
06-advertising-applications.jpg
```

不要使用你没有版权或授权的作品作为公开示例。

## License

MIT License。允许个人、教育和商业使用、修改与再发布，但需要保留许可声明。

如果你希望改成“个人免费 / 商业授权”，请在公开发布前替换 `LICENSE.md`。
