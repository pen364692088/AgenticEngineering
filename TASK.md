# TASK: Agentic Engineering 操作系统落地

## GOAL
在 AgenticEngineering 仓库中实现完整的 Agentic Engineering 工程规范与脚手架，
让后续任何长任务都能：测试导航、上下文记忆、并行分治、专业化分工、可重复性。

## Definition of Done (DoD)
- [ ] scripts/agent_run.sh 可用：终端输出受控 + reports/full.log + reports/summary.json + reports/run_meta.json
- [ ] test-smoke / test-fast / test-full 三入口存在且可运行
- [ ] fast 支持采样（1%/10%）或等价机制
- [ ] docs/STATUS.md / TODO.md / DECISIONS.md / HANDOFF.md 存在并填入真实内容
- [ ] docs/PARALLEL_WORK.md + worktree 脚本可用
- [ ] docs/ROLES.md + 5 个角色 prompts 完整
- [ ] CI（或本地钩子）已接入至少 smoke/fast
- [ ] 全部改动自洽、可复用到后续项目

## Phase
- phase: plan
- next_action: Phase 1 - 探测与规划，创建文档结构

## Blockers
- (none)

## Context
- 仓库：/home/moonlight/Project/Github/MyProject/AgenticEngineering
- Remote: https://github.com/pen364692088/AgenticEngineering.git
- 允许远端 push（owner=pen364692088）
