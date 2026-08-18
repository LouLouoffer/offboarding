# 来源

本 skill 来自开源项目 [aislinn-yang/rednote-writing-skill](https://github.com/aislinn-yang/rednote-writing-skill)，MIT License（见 `LICENSE`）。

- 引入版本：upstream commit `8e4bd7082ca2782ee872c10f4005b4e75ec90d49`
- 引入日期：2026-08-18

## 本地改动

1. 删掉了 `SKILL.md` frontmatter 里的 `allowed-tools: mcp__notion__...`。
   该字段是白名单，会把 skill 能用的工具限制成这几个 Notion MCP 工具；本仓库没有接
   Notion MCP，留着会让 skill 连自己的 `examples.md` 都读不了。删掉后按默认继承全部工具。
   如果之后接了 Notion MCP 并想收紧权限，把这一行加回去，并补上 `Read`、`Glob`、`Task` 等。

## 待你自己替换（否则 voice 不是你的）

- `examples.md`：目前是原作者（AI 产品增长 x 出海观察方向）的 8 篇真实帖子，是 voice 的唯一标准。
  换成你自己的代表作，这是最关键的一步。
- `SKILL.md` 的「账号」段落：定位、读者、个人背景。
- `checks.md` 的平台限流词库：按需增删。
- `SKILL.md` 的「保存到 Notion」：库链接还是占位符，填你自己的或整段删掉。
