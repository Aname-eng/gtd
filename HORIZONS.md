# HORIZONS — 德平 (last updated 2026-06-15)

> 跨会话同步：H4/H5 由本文件定义。H3 Goals 存 gtd CLI（`--horizon goal`）。H2 Areas 在本文件。H1 Projects 在 gtd milestones。Ground actions 在 gtd issues。
> 修改后请 commit 到 `~/gtd/HORIZONS.md`（已经是 git repo）。

---

## H2: Areas of Focus & Responsibility

- **工作/学习** — 南开大学经管类课程 + GTD 主目标（宏观/发展经济学研究）。期末考试季：6/23-6/30
- **个人生活** — 父母（重要他人）、健康（运动每周 3+ 次）、个人事务
- **副业/爱好** — 出门遛弯、吃好吃的、尝鲜（按 memory.md 偏好）

### 季度复盘问题
1. 哪个 area 我最近忽略了？
2. 当前项目分布是否均衡？
3. 我是否过度承诺？

---

## H3: Goals (1-2 年)

**位置**：gtd CLI（`gtd list --horizon goal`）

- 2026 目标：宏观经济学/发展经济学研究（gtd issue #2，已录入）

### 季度复盘问题
1. 我的目标有进展吗？
2. 这些还是对的目标吗？
3. 哪些项目支持这些目标？

---

## H4: Vision (3-5 年)

### 职业
- 在宏观/发展经济学方向成为有研究能力的学者/分析师
- 完成本科+研究生阶段核心训练，能独立做实证研究
- 在学术或政策圈有发声渠道

### 个人
- 保持规律运动，每周 3 次户外
- 跟父母保持紧密联系（至少每周一次电话）
- 维持稳定朋友圈和亲密关系

### 影响
- 用研究能力产出对真实世界有意义的洞察
- 帮同龄人少走弯路（GTD 体系 / 时间管理）

---

## H5: Purpose & Principles

### My Purpose
**用研究能力理解真实世界的经济问题，让世界少一点不确定。**

### My Principles
1. **先做最重要的**（GTD 核心：宏观/发展经济学 > 必修考试 > 选修/杂事）
2. **提早开始，不冲刺到深夜**（21:00 收工是底线）
3. **不刷手机，进度为先**（15 分钟粒度，今日事今日毕）
4. **身体是基础**（不舒服就停，复盘明天补）

### Decision Filter
当面临选择时我自问：
1. 这个选择支持我的 3-5 年 vision 吗？
2. 21:00 前能完成吗？（不行的就拆或推迟）
3. 我会为这个选择骄傲吗？

---

## Review Rhythms（已配置 cron）

### Daily (5 min)
- 工作日 7:30 / 周末 8:00 — `gtd daily` 自动跑（早间简报 cron）
- 23:00 — `gtd done` + 明日 handoff（日终复盘 cron）

### Weekly (15-30 min)
- 周日 23:00 复盘邮件加 "本周周复盘" 节
- 手动跑 `gtd weekly`

### Quarterly
- 手动跑 `gtd quarterly`，更新 H2 Areas

### Yearly
- 手动跑 `gtd yearly`，更新本文件
