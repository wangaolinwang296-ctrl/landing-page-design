# 冈部伦太郎专属版 landing-page-design

基于 elayadesign/ai-design-skills 的 `landing-page-design` 稍做修改后的个人版。

## 改了什么

原版视觉系统（字体、间距、圆角、动效）全部保留，全文已翻译成中文，并稍作修改：

1. 默认中文：全文中文，文案、标题、FAQ、按钮默认出中文，除非要求英文
2. 不编造：人物、证言、数字、收入、经历、功效以真实材料为准，没有材料就留空位标注待填
3. 电脑优先：买家大部分用电脑浏览，默认按桌面端设计，首屏、结构、CTA、排版先保证电脑端完整好用；移动端只要求不错乱、不遮挡
4. 免费路线优先：部署和第三方服务优先免费、无需绑卡的方案，出现收费或绑卡提示先停下
5. 个人品牌署名：为个人品牌做页面时，署名严格用「冈部伦太郎」

## 包含

- `skills/landing-page-design/SKILL.md`：完整技能文件
- `LICENSE`：原项目 MIT 协议

## 安装

Claude Code：

```bash
mkdir -p .claude/skills
cp -r skills/landing-page-design .claude/skills/
```

Cursor：把 `skills/landing-page-design/SKILL.md` 放入项目规则，或粘贴到 Settings → Rules for AI。

Codex / Windsurf / 其他：把 `SKILL.md` 放入工具对应的项目规则文件（Codex 用 `AGENTS.md`，Windsurf 用 `.windsurfrules`）。

装完重启工具，用 `/landing-page-design` 或直接说“做个落地页”即可。

## 来源与协议

原项目：elayadesign/ai-design-skills，MIT 协议。原 SKILL.md 文末 Credits 段保留未删。
