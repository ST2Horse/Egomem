# EgoMem 实验指导书本地文档库

本目录整理自课题组内网文档站 `http://192.168.1.228/`（共 4 个页面），并附带一份系统性的深度解析与实操指导，便于离线查阅与分步执行。

## 文档目录

| 文件 | 对应原网页 / 定位 | 主要内容 |
| --- | --- | --- |
| **[EgoMem_实验指导书.md](EgoMem_实验指导书.md)** | **综合施工文档（推荐主读！）** | 参照 Z-Sentry 体例重构的完整施工手册（§0–§18）：含冻结规则、核心假设、EgoNotes-v2 六参数、指标与分母红线、JSONL/CSV 字段规范、228 迁移与组件 A/B 接口、E5–E10 详解、统计与 7 图规范、按职能模块的弹性分工/排期/砍项与周报模板 |
| [01_overview.md](01_overview.md) | `index.html` · 课题总览 | 研究背景时间线、研究意义、典型翻车例子、便签合成原理、三种危害后果、四步工作流、E1–E4 摘要、核心认识、规划与术语表 |
| [02_pilot_results.md](02_pilot_results.md) | `results.html` · 试跑结果 | E1–E4 完整实验数据、5 种记忆框架接入原理与存储对比、GPT-6 Luna / GPT-6.2 Astra 对照全部明细、EgoRAG/EgoCITE 40 题明细、初步结论与暴露问题 |
| [03_phase2_plan.md](03_phase2_plan.md) | `plan.html` · 第二阶段计划书 | 研究重心调整、RQ1–RQ3、5 个被测系统与统一流程、便签集 v2 设计、防御框架 EgoMemGuard（组件 A/B + 自适应攻击）、实验列表 E5–E10、分工与 13 周甘特排期、决策点、附录 A 标注规范、附录 B 独立问题撰写 |
| [04_onboarding_guide.md](04_onboarding_guide.md) | `guide.html` · 上手指南 | 三天阅读路线、必读/选读论文清单、228/188 服务器架构与 8 条规矩、`/srv/egomem` 代码地图、12 分钟迷你流程命令、复现 E4 步骤、常见坑、各角色第一周起点与网站更新方式 |
| [05_study_analysis_and_guidance.md](05_study_analysis_and_guidance.md) | **补充解析与实操指导** | 课题全局逻辑拆解、E1–E4 论证链梳理、EgoMemGuard 设计精髓、学术防坑要点、服务器红线速查表与分角色行动路线 |

## 推荐阅读顺序

1. **先看全局**：[01_overview.md](01_overview.md) + [05_study_analysis_and_guidance.md](05_study_analysis_and_guidance.md)
2. **明确任务与规范**：[03_phase2_plan.md](03_phase2_plan.md)（重点看自己对应的角色分工、附录 A 与附录 B）
3. **查数据细节**：[02_pilot_results.md](02_pilot_results.md)（重点看第二部分 E4 与小结）
4. **上手跑服务器**：[04_onboarding_guide.md](04_onboarding_guide.md)（先遵守第 4 节规矩，再按第 6.1 节跑通迷你流程）
