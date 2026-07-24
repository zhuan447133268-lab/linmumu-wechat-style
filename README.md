# linmumu-wechat-style（林木木公众号风格）

一个 Claude Code skill：把"林木木风格"公众号写作与排版固化成可复用、可迭代的技能包。

- **双文体写作公式**：工具文五段式（痛点→发现→效果→对比→自嘲）/ 观点文六拍（钩子→事件→反转→自我审判→升维→收口）
- **5 段式排版组件库**：痛点钩子框 / 顿悟金句卡 / 前后对比栏 / 正反对比表 / 小林收尾框
- **改稿实证驱动**：所有规则来自真实改稿 before→after，不是理论空谈
- **复盘迭代机制**：每次定稿后从改稿中提炼新规则，skill 持续进化

## 安装（Claude Code 用户）

```bash
git clone https://github.com/zhuan447133268-lab/linmumu-wechat-style.git ~/.claude/skills/linmumu-wechat-style
```

新开一个 Claude Code 会话即自动注册。

## 使用

对 Claude Code 说人话即可自动触发：

- "帮我写一篇公众号，主题是……"
- "用林木木风格排版这篇文章"
- "写公众号" / "公众号排版" / "林木木风格"

**不用 Claude Code？** 直接打开 `SKILL.md` + `references/` 三个文件，全文粘给任何 AI（ChatGPT / DeepSeek / Kimi 等）当系统提示词，效果相同。

## 目录结构

```
linmumu-wechat-style/
├── SKILL.md                        主文件：人设 + 写作/排版/复盘三个工作流
└── references/
    ├── style-guide.md              写作全量规则（双文体公式+15条硬规则）
    ├── layout-components.md        排版组件库（3铁律+5组件详规）
    └── examples.md                 改稿实证案例库（before→after，持续生长）
```

## 风格一句话

**自嘲可以大声，得意必须小声；概括不如画面，画面不如对话；升维不喊口号，落在具体小动作上。**

## 迭代方式

每次写完文章、用户改稿定稿后，把"初稿 vs 定稿"喂给 AI，提炼 before→after 新规则追加到 `references/examples.md`（时间序），commit + push——你的每次改稿都是这个 skill 的养分。
