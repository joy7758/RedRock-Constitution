# RR-CORE-1.0 — RedRock Constitution Core / 红岩宪章核心（总标准）

Status / 状态：Draft（可评审）
Version / 版本：RR-CORE-1.0
Updated / 更新时间：2026-02-19 12:16 UTC+08:00

---

## 1. Purpose / 目的

**EN**
RR-CORE defines the *constitutional layer* of the RedRock system: how standards are named, governed, linked, and evolved.
It exists to secure **standard-definition power** (not “feature competition”).

**中文**
RR-CORE 定义红岩体系的“宪法层”：标准如何命名、治理、链接、演进。
它的目标是**标准定义权**，而不是“功能卷王”。

---

## 2. Core Positioning / 核心定位

**EN**
RedRock is a hub-first governance framework:
- Hub repository = Constitution + Registry + Roadmap
- Domain repositories = Implementations + experiments + demos
- Everything must be traceable to a standard domain ID.

**中文**
红岩是“中枢优先”的治理框架：
- 中枢仓库：宪章 + 注册表 + 路线图
- 标准域仓库：实现 + 实验 + 演示
- 一切内容必须可追溯到标准域编号。

---

## 3. Vocabulary / 术语

- **Hub / 中枢**：RedRock-Constitution
- **Standard Domain / 标准域**：以 `RR-*` 编号的领域单元（如 RR-pFDO）
- **Spec / 规范**：标准文本（可 CN/EN 镜像）
- **Implementation / 实现**：代码、原型、工具链
- **Evidence / 证据**：可复现脚本、输出、图表
- **Registry / 注册表**：标准域与状态的清单（Hub 内）

---

## 4. Standard ID Rules / 标准编号规则

**Domain IDs**
- `RR-pFDO`, `RR-AASP`, `RR-ISAS`, `RR-DOIP`, `RR-CPM`, `RR-KRFS`, `RR-MCP-LC`

**Spec IDs**
- `RR-<DOMAIN>-<NAME>-<MAJOR>.<MINOR>`
- Example: `RR-NSE-EC-1.0`

**中文**
- 域编号负责“归属”
- 规范编号负责“演进”
- 所有仓库必须声明自己属于哪个标准域。

---

## 5. Bilingual Policy / 双语策略

**Rule**
- Public-facing core docs: CN + EN must both exist.
- Allowed format:
  1) one file with CN section then EN section, or
  2) CN/EN mirror files (recommended for long specs).

**中文**
- 对外材料必须中英双语
- 可采用“同文件上下双语”或“CN/EN 镜像文件”。

---

## 6. Hub-First Navigation / 中枢优先导航

**EN**
All repositories must link back to Hub.
Hub must provide:
- Repos Index
- Standards Registry
- Roadmap
- Governance

**中文**
所有仓库必须反向指向中枢。
中枢必须提供：
- 仓库总导航
- 标准注册表
- 路线图
- 治理公约

---

## 7. Release Workflow / 发布流程

1) Draft → Review → Release
2) Release must include:
   - spec text
   - minimal implementation pointer
   - minimal evidence pointer (repro script or demo)
3) Registry status update required.

**中文**
Draft → 评审 → 发布  
发布必须包含：规范文本 + 实现入口 + 证据入口，并同步注册表状态。

---

## 8. Non-Goals / 非目标

- Not a “product brochure”
- Not a “single company internal manual”
- Not chasing features for vanity

**中文**
- 不是产品宣传册
- 不是单公司内部手册
- 不卷虚荣功能

---

## 9. Next / 下一步

- RR-CORE-1.0 评审通过后，所有标准域文档按该宪章统一格式化与注册。
- 建立机器可读 Registry（JSON）用于工具链自动化。

