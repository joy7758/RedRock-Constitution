# RedRock Constitution

## Bilingual Governance Notice
**中文说明**：RedRock 标准体系采用中文与英文双语发布，英文内容必须为完整翻译版本，不得以摘要替代全文。  
**English Notice**: The RedRock standards family is published in Chinese and English. English content must be a full translation, not a summary.

---

## Hub Navigation / 总入口导航

| Repository | Positioning (CN / EN) | Standards Entry | Demo / Product Entry |
| :--- | :--- | :--- | :--- |
| [`pFDO-Specification`](https://github.com/joy7758/pFDO-Specification) | 园区数字合规与物理层 FDO 参考实现 / Park digital compliance and physical-layer FDO reference implementation | [`docs/paper/digital_metabolism_entropy_control.md`](https://github.com/joy7758/pFDO-Specification/blob/main/docs/paper/digital_metabolism_entropy_control.md) | Local dashboard: `/park`; API docs: `/docs-cn`; bootstrap via [`scripts/run_park.sh`](https://github.com/joy7758/pFDO-Specification/blob/main/scripts/run_park.sh) |
| [`AASP-Core`](https://github.com/joy7758/AASP-Core) | 机器意识审计与数字代谢协议核心 / Core protocol for machine-consciousness audit and digital metabolism | [`README.md`](https://github.com/joy7758/AASP-Core/blob/main/README.md) | Research/protocol repository (no standalone product UI) |
| [`ISAS-Core`](https://github.com/joy7758/ISAS-Core) | 工业主权自治与 eFDO 参考实现 / Industrial sovereign autonomy and eFDO reference implementation | [`README.md`](https://github.com/joy7758/ISAS-Core/blob/main/README.md) | Local node bootstrap via project scripts |
| [`DOIP-Segments-Specification`](https://github.com/joy7758/DOIP-Segments-Specification) | DOIP 分段与扩展操作标准对象库 / DOIP segment schemas and extended operation definitions | [`README.md`](https://github.com/joy7758/DOIP-Segments-Specification/blob/main/README.md) | Protocol/spec repository (schema-first) |
| [`MCP-Legal-China`](https://github.com/joy7758/MCP-Legal-China) | 中国法律增强与 MCP 合规插件 / China legal enhancement and MCP compliance plugin | [`README.md`](https://github.com/joy7758/MCP-Legal-China/blob/main/README.md) | Plugin/service integration entry in repository docs |
| [`Kinetic-Robotics-FDO-Sovereignty`](https://github.com/joy7758/Kinetic-Robotics-FDO-Sovereignty) | 机器人动作主权与 K-FDO 规范 / Robotics action sovereignty and K-FDO specification | [`docs/K-FDO-Sovereignty-Spec.md`](https://github.com/joy7758/Kinetic-Robotics-FDO-Sovereignty/blob/main/docs/K-FDO-Sovereignty-Spec.md) | Specification-driven implementation, no public dashboard |
| [`China-Precision-Mold-FDO-Standard`](https://github.com/joy7758/China-Precision-Mold-FDO-Standard) | 精密模具资产化 FDO 标准 / Precision-mold assetization FDO standard | [`README.md`](https://github.com/joy7758/China-Precision-Mold-FDO-Standard/blob/main/README.md) | Implementation and deployment entry in repository docs |
| [`RedRock-Constitution`](https://github.com/joy7758/RedRock-Constitution) | 标准家族总宪章与统一治理枢纽 / Constitutional hub for the standards family | [`GOVERNANCE.md`](https://github.com/joy7758/RedRock-Constitution/blob/main/GOVERNANCE.md) | Multi-repo navigation and governance baseline |

---

## Standards Registry / 标准族谱

| Standard ID | English Name | 中文名称 | Link |
| :--- | :--- | :--- | :--- |
| NSE-EC-1.0 | Digital Metabolism Entropy Control | 数字代谢熵控制 | [`pFDO-Specification/docs/paper/digital_metabolism_entropy_control.md`](https://github.com/joy7758/pFDO-Specification/blob/main/docs/paper/digital_metabolism_entropy_control.md) |
| AASP-3.0 | Adaptive Agent Sovereignty Protocol | 自适应代理主权协议 | [`AASP-Core/README.md`](https://github.com/joy7758/AASP-Core/blob/main/README.md) |
| EIS-2026 | Industrial Sovereign Autonomy Standard | 工业主权自治标准 | [`ISAS-Core/README.md`](https://github.com/joy7758/ISAS-Core/blob/main/README.md) |
| DOIP-SEG-2.0 | DOIP Segments Specification | DOIP 分段规范 | [`DOIP-Segments-Specification/README.md`](https://github.com/joy7758/DOIP-Segments-Specification/blob/main/README.md) |
| K-FDO-1.0 | Kinetic FDO Sovereignty Specification | 动力学 FDO 主权规范 | [`Kinetic-Robotics-FDO-Sovereignty/docs/K-FDO-Sovereignty-Spec.md`](https://github.com/joy7758/Kinetic-Robotics-FDO-Sovereignty/blob/main/docs/K-FDO-Sovereignty-Spec.md) |
| CPM-FDO-1.0 | China Precision Mold FDO Standard | 中国精密模具 FDO 标准 | [`China-Precision-Mold-FDO-Standard/README.md`](https://github.com/joy7758/China-Precision-Mold-FDO-Standard/blob/main/README.md) |

---

## Roadmap / 路线图

- **CN**：完成全部核心仓库 `docs/REPOS.md` 的双语统一与自动化校验脚本。  
  **EN**: Complete bilingual `docs/REPOS.md` normalization and automated validation scripts across all core repositories.
- **CN**：建立标准编号注册机制，新增标准需先完成 Registry 预登记。  
  **EN**: Establish a standard-ID registration workflow; new standards must be pre-registered in the Registry.
- **CN**：打通小程序/官网统一入口，消费 `docs/REPOS.md` 与 Standards Registry。  
  **EN**: Integrate mini-app/website hub to consume `docs/REPOS.md` and the Standards Registry.
- **CN**：形成双语发布检查清单（命名、镜像完整度、链接可达性）并纳入 CI。  
  **EN**: Add bilingual release checks (naming, mirror completeness, link reachability) into CI.
