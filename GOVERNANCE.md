# RedRock Constitution Governance Policy

## 1. Bilingual Mandate / 双语强制规则

### 中文
- 所有标准、规范、技术备忘录必须采用中文与英文双语发布。
- 英文必须为完整翻译版本，不得以摘要、提纲或片段替代。
- CN/EN 两个版本必须在同一发布窗口内同步生效。

### English
- All standards, specifications, and technical memos shall be published in both Chinese and English.
- English content must be a full translation and cannot be replaced by summary, outline, or partial fragments.
- CN/EN versions must become effective within the same release window.

## 2. Standard Identifier Rule / 标准编号规则

### 中文
- 统一编号格式：`RR-<DOMAIN>-<NAME>-<MAJOR>.<MINOR>`。
- `DOMAIN` 表示标准域（如 NSE、AASP、DOIP、ISAS）。
- 每个编号在标准注册表中必须唯一，且不得复用。

### English
- Unified identifier format: `RR-<DOMAIN>-<NAME>-<MAJOR>.<MINOR>`.
- `DOMAIN` denotes the standards domain (for example NSE, AASP, DOIP, ISAS).
- Each identifier must be unique in the standards registry and shall never be reused.

## 3. Versioning Rule / 版本规则

### 中文
- **Major** 版本变更用于语义不兼容更新或治理约束重构。
- **Minor** 版本变更用于兼容性增强、条款补充、术语澄清。
- 版本变更必须在 `docs/registry/STANDARDS_REGISTRY.md` 留痕，并更新状态字段（Draft / Release / Experimental）。

### English
- **Major** increments are for semantic breaking changes or governance model restructuring.
- **Minor** increments are for backward-compatible enhancements, clause expansion, and terminology clarification.
- Every version change must be recorded in `docs/registry/STANDARDS_REGISTRY.md` with updated status (Draft / Release / Experimental).

## 4. Release Process / 发布流程

### 中文
1. 提案阶段：提交标准草案并申请注册编号。  
2. 镜像阶段：完成 CN/EN 全量镜像并通过链接可达性检查。  
3. 审核阶段：完成跨仓库一致性审阅（编号、状态、入口、版本）。  
4. 发布阶段：合并至 `main`，更新 Registry 与 Roadmap，并记录发布日期。  

### English
1. Proposal stage: submit a draft standard and request a registry identifier.  
2. Mirroring stage: complete full CN/EN mirroring and pass link reachability checks.  
3. Review stage: complete cross-repository consistency review (identifier, status, entrypoint, version).  
4. Release stage: merge into `main`, update Registry and Roadmap, and record release date.
