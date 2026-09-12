# 偷师 Skill

把 GitHub 项目、本地代码或外部方法拆成一份“双层偷师报告”：

1. **先看懂**：还原完整架构、执行链路、CLI/API、数据流、判断分支、失败回退与证据位置。
2. **再化用**：逐项判断哪些值得保留、怎么改、哪些暂时不要碰，并改造成自己的工作流。

## 适合什么场景

- 看懂一个 GitHub 仓库或本地代码项目是如何设计和运行的
- 拆解一个 Skill 的触发条件、输入、流程、判断、输出和边界
- 从课程、文章、视频或 PDF 中提炼可复用的方法
- 输出浅色、易读的 HTML 报告和可编辑 Markdown 底稿

## 安装

把本仓库放入 Codex 的 Skills 目录：

```bash
git clone https://github.com/zzshuaiteacher-collab/toushi-skill.git ~/.codex/skills/toushi
```

也可以从 SkillHub 搜索 `toushi` 安装。

## 使用示例

```text
用偷师拆解 https://github.com/owner/repo
```

```text
用偷师拆解这个 Skill。先让我看懂完整架构，再告诉我哪些能为我所用。
```

## 输出原则

- 不拿 README 代替真实源码
- 不虚构 CLI、API、自动调度或数据流
- 重要结论尽量保留 `路径:行号` 证据
- 用户业务信息不足时标记 `〔待用户确认〕`
- “看懂外部对象”和“改造成自己的版本”必须同时交付

## 目录

```text
.
├── SKILL.md
├── agents/openai.yaml
├── assets/report-template.html
└── references/
    ├── adaptation.md
    ├── architecture-report.md
    ├── code-reading.md
    ├── cream-report-style.md
    └── fresh-report-style.md
```

当前版本：`v1.1.0`

## 许可证

本仓库目前未声明开源许可证。代码公开可见不等于授权复制、修改、分发或商用。
