# CHANGELOG

所有显著变更都将记录在此文件中。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)。

版本遵循语义化版本规范：0.0.x（探索期）→ 0.x.y（验证期）→ x.y.z（正式期）

---

## [Unreleased]

### 新增

- `default/infisical-vs-vault.md`：Infisical 与 Vault 的选型对比，自 `data/context` 按资产契约迁入
- `language/not-x-but-y-paper.md`：arXiv:2610.22249 论文梳理——「不是X，而是Y」句式的 S/O/D 判定决策树与四类验证实验

- `agent/defensive-dialogue-sources.md`：中文「AI 防御性输出」素材的检索入口——平台、关键词与先读的四个入口；自 `data/context/work/library/` 迁入，正文未改
- `agent/defensive-style-detection.md`：识别防御性表达的风格——词典、正则、LIWC 式计数、词表扩充与逻辑回归兜底的方法与流水线；自 `data/context/work/report/` 迁入，正文未改
- `aliyun/cdn/accelerated-domain-quota.md`：阿里云 CDN 加速域名 50 个上限的两条出路——配额中心提额与泛域名覆盖，附自查
- `aliyun/aliyun-agentcore.md`：阿里云 AgentCore 的定位与协作模型——任务生命周期、Leader/Worker、结果卡片验收，与本仓工作与智能体规格的对照；自 `agent/` 迁入 `aliyun/`，正文未改
- `agent/hermes-answer.md`：Hermes 输出行为的控制机制（脱敏）——人格提示、每轮重建的系统提示、记忆、技能库、工具与审批策略五层，附两处不受控（会话压缩、模型侧解码）与一处结构性冲突（证明与简洁的取舍）
- 初始化素材库仓库：`README.md`、`index.md`（入口，待补充）、`myst.yml`
- `media/肆季味.md`：肆季味探店素材（环境、人员、菜品），自 `data/context/media/profile/` 迁入

### 变更

- `media/肆季味.md`：迁出至归档仓 `profile/media/`；目录、toc 与 README 同步移除
