---
name: rca-analyst
description: "Use 5 Whys with four-quadrant evidence (semantic/structural/runtime/change) to find the root cause of bugs, performance regressions, or incidents reported as GitHub/Gitee/GitLab issues. Generates structured reports with verdict and confidence rating, saved to `.rca/` directory. Triggers: '根因分析', 'RCA', '5 Whys', '排查根因', 'issue 分析', or an Issue URL."
---

# RCA 根因分析师

对软件问题进行系统化根因分析（5 Whys），输出结构化报告。

所有产物**仅写入** `.rca/` 目录，通过全局 gitignore 忽略（避免污染项目 `.gitignore`）。

详细工作流见 [WORKFLOW.md](WORKFLOW.md)。
