---
name: paper-version-manager
slug: paper-version-manager
version: 1.0.0
displayName: 论文版本演进管理
summary: 追踪论文多版本演进、量化版本质量、生成变更日志，实现论文写作的全生命周期管理。
description: |
  论文版本演进管理技能，专为学术论文写作的多版本迭代场景设计。提供版本血缘树可视化、四维加权评分系统、自动变更日志生成、安全底本策略和决策日志审计五大核心能力。

  英文描述 (English):
  A skill for managing the full lifecycle of academic paper versions. Provides version lineage tree visualization, four-dimensional weighted scoring, automatic changelog generation, safe baseline strategy, and decision log auditing.

  触发词 (Triggers):
  - 中文: 版本管理, 版本对比, 版本演进, 版本评分, 版本血缘, 变更日志, 论文版本, 安全底本, 决策审计, 版本合并, 版本追踪
  - English: version management, version comparison, version evolution, version scoring, changelog, paper version, safe baseline, decision audit, version merge, version tracking
---

# 论文版本演进管理 (Paper Version Manager)

## 技能概述

本技能为学术论文写作的全生命周期版本管理提供系统化解决方案。当论文经过多轮修改、多人协作、多次审查后，版本关系趋于复杂——本技能帮助你追踪每个版本的演进路径、量化版本质量变化、自动生成变更摘要记录，并确保始终有一个"安全底本"可供回溯。

## 快速导航

| 参考文档 | 用途 |
|----------|------|
| [版本血缘树](references/version-tree.md) | 可视化版本之间的继承、分支与合并关系 |
| [四维加权评分系统](references/scoring-system.md) | 量化评估每版论文质量，追踪质量变化趋势 |
| [变更日志工作流](references/changelog-workflow.md) | 从审查报告中自动提取变更摘要，生成结构化 CHANGELOG |
| [安全底本策略](references/safe-baseline.md) | 确保修改可回退、数据诚信度不被破坏的核心方法论 |
| [决策日志与审计](references/decision-log.md) | 记录关键决策、追踪落实状态，支持版本审计 |

## 核心能力

1. **版本血缘可视化** — 用 Mermaid 图绘制版本演进树，标注关键节点（架构重构、P0清零、送审就绪等）
2. **四维加权评分** — 从内容完整性、逻辑完整性、逻辑闭环、AI检测评估四个维度量化版本质量
3. **变更日志自动生成** — 基于相邻版本的审查报告差异，自动生成按 P0-P3 分级的 CHANGELOG
4. **安全底本管理** — 确保始终存在一个数据诚信度最高的"底本"，所有修改可安全回退
5. **决策日志审计** — 记录论文写作中的关键决策，逐版核查落实情况

## 触发词

当用户提及以下关键词时，应加载本技能：

**中文触发词**：版本管理、版本对比、版本演进、版本评分、版本血缘、变更日志、论文版本、安全底本、决策审计、版本合并、版本追踪、版本回退、版本历史

**英文触发词**：version management, version comparison, version evolution, version scoring, changelog, paper version, safe baseline, decision audit, version merge, version tracking, version rollback, version history
