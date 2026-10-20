# CHANGELOG

所有显著变更都将记录在此文件中。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)。

版本遵循语义化版本规范：0.0.x（探索期）→ 0.x.y（验证期）→ x.y.z（正式期）

---

## [Unreleased]

### 新增

- `agent/aliyun-agentcore.md`：阿里云 AgentCore 的定位与协作模型——任务生命周期、Leader/Worker、结果卡片验收，与本仓工作与智能体规格的对照
- `agent/hermes-answer.md`：Hermes 输出行为的控制机制（脱敏）——人格提示、每轮重建的系统提示、记忆、技能库、工具与审批策略五层，附两处不受控（会话压缩、模型侧解码）与一处结构性冲突（证明与简洁的取舍）
- 初始化素材库仓库：`README.md`、`index.md`（入口，待补充）、`myst.yml`
- `media/肆季味.md`：肆季味探店素材（环境、人员、菜品），自 `data/context/media/profile/` 迁入
