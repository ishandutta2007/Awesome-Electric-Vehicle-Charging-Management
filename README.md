# Awesome-Electric-Vehicle-Charging-Management

# 顶级电动汽车充电管理平台生态系统

**精选 SaaS 产品与开源 GitHub 项目列表**
*聚焦充电站管理、OCPP 协议、智能充电与车网互动*
**最后更新：2026 年 9 月**

本仓库追踪**电动汽车充电管理**领域的知名 **SaaS 平台**与**开源项目**。这些工具帮助充电运营商 (CPO)、车队管理者和能源公司管理充电站网络、处理支付、优化能源使用，并确保符合 OCPP/OCPI 等开放标准。

**示例**包括 AMPECO、Driivz、ChargeLab、EV Connect、GreenFlux、Virta、Monta、Shell Recharge Solutions、ChargePoint 和 Wallbox Business（该领域的领先者）。

**开源重点**：电动汽车充电的开源生态**正在快速成熟**。**SteVe** 是最成熟的开源 OCPP 服务器，自 2013 年起在 RWTH 亚琛工业大学开发，拥有超过 1,000 个 GitHub 星标 。**EVerest** 由 Linux 基金会支持，是充电站的开源固件栈，支持 OCPP 1.6、2.0.1 和 ISO 15118 。**CitrineOS** 是 LF Energy 项目，基于 OCPP 2.0.1 构建，2025 年新增了对 OCPP 1.6 的支持 。本列表重点收录这些可自托管的生产级方案。

欢迎贡献！提交 PR 以添加/更新条目。保持描述事实性，并链接到官方网站。

## 目录

- [SaaS/托管平台](#saas托管平台)
- [开源 GitHub 项目](#开源github项目)
- [如何贡献](#如何贡献)
- [免责声明](#免责声明)

## SaaS/托管平台

- **[AMPECO](https://www.ampeco.com/)**
  保加利亚充电管理平台，2024 年 9 月被 E.ON Drive Infrastructure 选为充电管理平台提供商，用于管理 11 个国家超过 6,000 个公共充电器 。提供完整的 CPMS 功能，包括充电站管理、支付、漫游和智能充电。

- **[Driivz](https://driivz.com/)**
  2024 年 11 月推出 Platform V8，新增网络状态仪表板、大规模充电器运营、能源管理和基于车队保有量的报告功能 。平台专注于将运营工作流与能源工作流在企业部署环境中整合。

- **[ChargeLab](https://chargelab.co/)**
  硬件无关的充电管理软件，支持 OCPP 合规的充电站。为充电运营商提供监控、管理和优化工具。

- **[EV Connect](https://www.evconnect.com/)**
  充电站管理平台，2025 年市场份额为 2.61%（9000 万美元）。提供充电网络运营、驾驶员支持和车队管理功能。

- **[GreenFlux](https://www.greenflux.com/)**
  荷兰充电管理平台（被 DKV Mobility 收购）。提供 CPMS、漫游和智能充电解决方案，专注于欧洲市场。

- **[Virta](https://www.virta.global/)**
  芬兰充电管理平台。提供充电站管理、驾驶员应用和能源服务，专注于北欧和欧洲市场。

- **[Monta](https://monta.com/)**
  丹麦充电平台，面向充电运营商、企业和驾驶员。提供充电站管理、支付、家庭充电和车队解决方案。

- **[Shell Recharge Solutions](https://shellrecharge.com/)**
  Shell 的充电管理平台（前身为 NewMotion）。提供充电站管理、漫游和商业充电解决方案。

- **[ChargePoint](https://www.chargepoint.com/)**
  北美最大的充电网络运营商，2025 年市场份额 5.66%（1.95 亿美元）。提供完整的充电管理平台，包括充电站管理、驾驶员应用和订阅服务。

- **[Wallbox Business](https://wallbox.com/)**
  充电硬件制造商提供的商业充电管理解决方案。提供充电站管理、支付和能源管理功能。

## 开源 GitHub 项目

### OCPP 服务器与充电站管理系统 (CSMS)

- **[SteVe](https://github.com/steve-community/steve)**
  最成熟的开源 OCPP 服务器实现，自 2013 年在 RWTH 亚琛工业大学开发。名称源自德语 *Steckdosenverwaltung*（插座管理）。支持 OCPP 1.2S、1.2J、1.5S、1.5J、1.6S、1.6J。提供充电点管理、用户数据和 RFID 卡管理的基本功能。Docker 部署支持。**Java，GPL-3.0**。714 个 GitHub 星标 。注意：当前不支持 OCPP 1.6 安全白皮书，公开实例存在安全风险 。

- **[CitrineOS](https://github.com/citrineos/citrineos-core)**
  LF Energy 项目的开源充电站管理系统，由 S44 Energy 开发并捐赠。**基于 OCPP 2.0.1 构建**，2025 年新增 OCPP 1.6 支持，扩展了对传统充电器的兼容性 。采用模块化架构，新增动态 UI、GraphQL 支持和 S3 兼容的 MinIO 文件存储 。**TypeScript，Apache-2.0**。

- **[MaEVe](https://github.com/maeve-tech/maeve)**
  实验性电动汽车充电站管理系统 (CSMS)。**88 个 GitHub 星标**，活跃开发中 。

- **[Open e-Mobility (SAP Labs France)](https://github.com/sap-labs-france/ev-server)**
  SAP Labs France 的开源充电站管理后端服务器。包含 ev-dashboard（Angular 前端，79 星）和 ev-mobile（React-Native 移动应用，48 星）。**TypeScript，170 星**。

- **[gregszalay/ocpp-csms](https://github.com/gregszalay/ocpp-csms)**
  现代、可扩展的 OCPP 2.0.1 充电站管理系统。**Go 语言**，36 个 GitHub 星标 。

### 充电站固件与操作系统

- **[EVerest](https://github.com/EVerest/EVerest)**
  Linux 基金会 (LF Energy) 支持的开源电动汽车充电站固件栈。由 PIONIX GmbH 于 2020 年发起，**贡献组织包括 ABB、Siemens、Tesla、Eaton、NREL 等** 。支持从无管理的 AC 家用充电器到复杂的多 EVSE 公共 DC 充电站（带电池和太阳能支持）。支持 OCPP 1.6、2.0.1 和 ISO 15118，提供标准合规、互操作和安全的充电 。**C++，Apache-2.0**。

- **[CIP.io Link](https://github.com/cip-io/cip-io-link)**
  阿贡国家实验室 (ANL) 开发的开源、供应商中立的本地 EV 充电控制器。支持 OCPP 1.6J，提供实时仪表板、负载均衡和智能充电控制。**本地部署，无云依赖**，降低基础设施和网络成本，提供完整的数据所有权 。**开源**。

- **[Josev](https://github.com/josev-community/josev)**
  V2G 充电站的社区版操作系统。**129 个 GitHub 星标**，支持 ISO 15118 通信协议 。

### OCPP 库与工具

- **[Java-OCA-OCPP](https://github.com/ChargeTimeEU/Java-OCA-OCPP)**
  开放充电点协议 (OCPP) 的开源客户端和服务器库，由 Open Charge Alliance 定义。**353 个 GitHub 星标**，活跃维护中 。**Java**。

- **[mobilityhouse/ocpp](https://github.com/mobilityhouse/ocpp)**
  Python 实现的 OCPP 库。**997 个 GitHub 星标**，是 Python 生态中最流行的 OCPP 实现 。

- **[MicroOcpp](https://github.com/matth-x/MicroOcpp)**
  面向微控制器的 OCPP 1.6/2.0.1 客户端。**509 个 GitHub 星标**，适合嵌入式充电器开发 。

- **[OCPP 2.0 Charge Point Simulator](https://github.com/ChargeTimeEU/OCPP-2.0-CP-Simulator)**
  OCPP 2.0 充电点模拟器。**58 个 GitHub 星标**，用于测试和开发 。

### 其他强开源选项

- **OCPP 服务器**：**SteVe**（最成熟，GPL-3.0）、**CitrineOS**（OCPP 2.0.1 + 1.6，Apache-2.0）、**MaEVe**（实验性）、**Open e-Mobility**（SAP Labs）。
- **充电站固件**：**EVerest**（LF Energy，行业支持）、**CIP.io Link**（本地控制，无云依赖）。
- **OCPP 库**：**Java-OCA-OCPP**（Java）、**mobilityhouse/ocpp**（Python，997 星）、**MicroOcpp**（嵌入式，509 星）。
- **V2G/ISO 15118**：**Josev**（V2G 操作系统）、**RISE-V2G**（ISO 15118 参考实现）。

**构建自定义系统的框架**：结合 **SteVe** 或 **CitrineOS** 作为 OCPP 服务器核心，**EVerest** 作为充电站固件，**mobilityhouse/ocpp** 或 **Java-OCA-OCPP** 用于协议库，**CIP.io Link** 用于本地智能充电控制。添加 **PostgreSQL/MySQL** 用于持久化，**Docker** 用于部署。

## 如何贡献

1. Fork 仓库。
2. 在 `README.md` 中添加/编辑条目（遵循现有格式）。
3. 包含：名称、链接、1-2 句描述，以及是 SaaS 还是开源。
4. 提交 PR 并附简短说明。

如果你觉得这个仓库有用，请点星！

## 免责声明

- 这是一个**社区精选**列表——并非详尽无遗，也不构成认可。
- 电动汽车充电平台处理敏感的支付和用户数据；确保符合 PCI DSS、GDPR 和相关充电法规。
- **开源现实**：电动汽车充电的开源生态在 **OCPP 服务器**（SteVe、CitrineOS）和 **充电站固件**（EVerest）层面已经成熟且生产就绪 。但在**完整的 CPMS 商业功能**（支付处理、漫游、驾驶员应用、白标门户）层面，开源方案需要大量自定义开发。商业平台（AMPECO、Driivz、ChargePoint）仍主导企业级部署。

---

**为充电运营商、车队管理者、能源公司和电动汽车基础设施开发者打造。**
让电动汽车充电管理更开放、互操作、可扩展。
