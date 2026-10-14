<div align="center">

# 🎬 lark-approval

## 待办一堆？一句话查完审批，还能顺手把评论回掉
## Stop drowning in approvals—query, comment, and submit in one shot

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

这是一个审批处理技能，把查询和处理审批待办、已办、审批实例的能力收进一条命令。它还能搜索可发起的审批定义、查看定义详情，并直接发起原生审批实例。审批评论同样覆盖：查询、创建、回复、编辑、删除一步到位。技能内置路由优先级，先判断任务是不是审批，避免把非审批待办错误路由，也减少无效重试和无效消耗。

### ✨ 能做什么

- 查询并处理审批待办 / 已办 / 审批实例
- 搜索可发起的审批定义，查看定义详情后直接发起原生实例
- 查询、创建、回复、编辑、删除审批评论
- 先用路由优先级判断「是不是审批」，再选具体命令
- 先取最小必要信息再执行，已知对象时直达动作
- 明确不接管非审批类待办（走任务技能），也不创建审批定义

### 📦 包含的技能

- `lark-approval` —— 见 [`lark-approval/SKILL.md`](lark-approval/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/lark-approval.git
cp -r lark-approval/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

This skill handles approval work end to end: querying and acting on pending, done, and instance records, searching for requestable approval definitions, reading their details, and submitting native approval instances. Comments are covered too—query, create, reply, edit, and delete. Built-in routing priority first decides whether a request is approval work at all, cutting misrouting, blind retries, and wasted calls. It does not create approval definitions, and third-party approvals skip native submission.

### ✨ What it does

- Query and act on approval to-dos, done items, and instances
- Search requestable approval definitions, inspect details, submit native instances
- Query, create, reply to, edit, and delete approval comments
- Decide 'is this approval at all?' before picking a command
- Grab the minimum info first; go straight to the action when the object is known
- Explicitly hands non-approval to-dos to the task skill and never creates definitions

### 📦 Skills included

- `lark-approval` — [`lark-approval/SKILL.md`](lark-approval/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/lark-approval.git
cp -r lark-approval/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
