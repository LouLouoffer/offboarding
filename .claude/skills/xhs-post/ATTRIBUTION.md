# 来源

本 skill 来自开源项目 [aislinn-yang/rednote-writing-skill](https://github.com/aislinn-yang/rednote-writing-skill)，MIT License（见 `LICENSE`）。

- 引入版本：upstream commit `8e4bd7082ca2782ee872c10f4005b4e75ec90d49`
- 引入日期：2026-08-18

## 本地改动

1. **删掉 `SKILL.md` frontmatter 的 `allowed-tools: mcp__notion__...`。**
   该字段是白名单，会把 skill 能用的工具限制成那几个 Notion MCP 工具；本仓库没接
   Notion MCP，留着会让 skill 连自己的 `examples.md` 都读不了。删掉后按默认继承全部工具。
   之后若接了 Notion MCP 并想收紧权限，把这行加回去，并补上 `Read`、`Glob`、`Task` 等。

2. **`examples.md` 整个换掉。** 原作者的 8 篇（AI 产品增长 x 出海观察）换成 5 篇
   纽约中古探店帖（Noris Vintage 相关），逐字转录 + 逐篇拆解 + 末尾「共性拆解」。
   数据最差的一篇（9赞）保留作反面参照。

3. **`SKILL.md` 按中古品类重调**：账号定位改成 Pariss Vintage 主理人，新增「三种身份」
   （主理人 / 个人探店 / 留学生活）和「起号期策略」；语感特征、hashtag 池、信息块位置
   全部换成这个品类的。

4. **`cover-title.md` 放开标题 emoji**（限 1-2 个且要有功能）。参照帖每篇标题都带 emoji，
   原来的「标题无 emoji」死规则和这个品类冲突。

5. **`checks.md` 调三处**：信息块字段名后允许用冒号（「地址：xxx」）；「空泛评价词」加进
   结构性 AI 味；第四章第二层的高危词库从 SEO / 时政改成中古品类的（真伪承诺、站外交易
   导流、促销硬广词、品牌词密度）。

## 关于 examples.md 的重要说明

**里面 5 篇是别人发布的帖子，不是本人写的。** 所以现在 skill 学到的是「纽约中古探店这个
品类怎么写」，不是「你的声音」。这是刚起号阶段的临时方案。

自己发过几篇之后回来做这一步：把其中写得最顺、数据最好的 2-3 篇加进 `examples.md`，
标上「本人原创，voice 基准」，让 skill 优先照你自己的写。参照帖可以留着当品类手感。

## 其他待办

- `SKILL.md` 的「保存到 Notion」：库链接还是占位符，填你自己的或整段删掉。
- `SKILL.md` 的「起号期策略」：等账号有量了回来删掉。
- `checks.md` 第四章第二层：被限流之后把真实命中的词补进去，标日期，越用越准。
