# 偷师报告的米黄色纸张风格

> 历史参考，已停用。以下保留旧版记录，不作为执行要求。v1.0.0 以 `SKILL.md`、`architecture-report.md` 与 `fresh-report-style.md` 为准：完整架构与逐层链路在前，逐项验货和我的版本在后；不要采用本文旧版的视觉顺序。

最终 `偷师报告.html` 是主要交付，不可直接拿 Repo Explainer 的默认深色报告交差。

## 必要视觉变量

```css
:root {
  --page: #F5EAD5;
  --paper: #FFFDF6;
  --paper-soft: #FBF4E5;
  --ink: #3F3629;
  --ink-muted: #756857;
  --line: #E4D4BB;
  --accent: #8A5A2B;
  --accent-soft: #D7B98D;
  --sage: #6E7E58;
  --warn: #B64D36;
}
body { background: var(--page); color: var(--ink); }
.card, .section { background: var(--paper); border-color: var(--line); }
```

## 禁止项

- 不使用 `midnight`、深蓝、纯黑背景或蓝紫霓虹渐变。
- 不用“技术驾驶舱”式卡片堆砌掩盖吸星大法的验证内容。
- 不将源码结构表放在验证表和“我的版本”之前占据主要视觉篇幅。

## 页面检查

1. 页面首次打开先看到一句结论和“值不值得吸”。
2. 验证表与“我的版本”占据视觉主体。
3. `路径:行号` 证据保留，但置于辅助位置。
4. 输出后应在浏览器或截图中检查：正文与背景对比足够、中文可读、流程图箭头方向正确。
