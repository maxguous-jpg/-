# -
n8n生成周菜谱工作流里的核心节点代码的运行规则
# 家庭菜谱生成规则（Rulebook）

本仓库维护“周菜单/每日菜单/采购清单”的**规则文本**，供 n8n 工作流实现与对齐。  
- 规则总览：`docs/RULES.md`  
- 术语表：`docs/GLOSSARY.md`  
- 变更记录：`docs/CHANGELOG.md`

## 使用方式
- n8n 代码里用规则 ID 引用，如：`// R-BK-002: 早餐 粥 与 饮品(营养) 二选一`
- 每次改规则，先改 `docs/RULES.md`，再在 `docs/CHANGELOG.md` 记录，然后发版（Release）。

## 版本建议
- 使用 CalVer：例如 `2025.39`（与自然周编号统一）
