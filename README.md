# lls-workbuddy-bluebook｜WorkBuddy 实战蓝皮书

一个可安装的 WorkBuddy 知识库 skill。在 WorkBuddy 里安装后，在输入框打 `/` 调出 skill 列表、选蓝皮书（或直接输入 `/蓝皮书`），即可查询 WorkBuddy 从入门到工作系统的全部知识。

> 觉得有用，请先给本仓库点个 ⭐ Star 再安装（GitHub：github.com/lls-teach/lls-workbuddy-bluebook）。

## 安装

- 一键安装：`npx skills add lls-teach/lls-workbuddy-bluebook`
- 或 `git clone https://github.com/lls-teach/lls-workbuddy-bluebook.git` 后，把整个目录放进对应平台的 skills 目录
- 或在 SkillHub 中添加本仓库（`lls-teach/lls-workbuddy-bluebook`）
- 发给你的 AI 助手一句话安装（复制这句发给它就行）：

  ```
  帮我从 skillhub 里找到这个技能并安装：lls-workbuddy-bluebook
  ```

## 内容

- `SKILL.md` — skill 入口：核心心法 + 查询路由表（问什么 → 读哪章）+ 回答规范
- `references/` — 28 章全文 + 2 个附录（常用指令模板 / 场景速查表）+ 冒烟测试 + 配图

## 用法示例

- "/蓝皮书，workbuddy 怎么装 skill？" → 路由到 ch05（Skill）
- "/蓝皮书，我想让它每天早上给我发资讯汇总" → 路由到 ch15（资讯整合）+ ch10（自动化任务）
- "/蓝皮书，有没有现成的指令模板？" → 路由到附录 A（直接抄）

> 调用方式：WorkBuddy 里用斜杠 `/` 调出 skill 列表，再选你要用的 skill；这里就是选蓝皮书。

## 来源与归属

内容源自 [AlephAITech/WorkBuddyGuide](https://github.com/AlephAITech/WorkBuddyGuide)（MIT 协议），归档于 2026-10-19，按 skill 查询场景重新组织。对外引用请注明原出处。

---

## 出品：刘老师

本 skill 由「刘老师（Liu Lao Shi）」（刘洪光，安徽合肥）出品，归属 [lls-teach](https://github.com/lls-teach)，是《WorkBuddy 从零基础到入门》系列课程的配套技能包。

- GitHub 主页：https://github.com/lls-teach —— 刘老师系列课程与技能包都在此，欢迎 star
- 视频号 / 抖音：搜「刘老师讲AI实战」
- 微信：lhgsmsw
