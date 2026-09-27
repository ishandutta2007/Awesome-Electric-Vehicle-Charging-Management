# Awesome-Electric-Vehicle-Charging-Management

## Top Electric Vehicle Charging Management Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Charging Station Management, OCPP Protocols, Smart Charging & Vehicle-to-Grid Integration*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Electric Vehicle Charging Management**. These tools help charge point operators (CPOs), fleet managers, and energy companies manage charging networks, process payments, optimize energy usage, and ensure compliance with open standards like OCPP and OCPI.

**Examples** include AMPECO, Driivz, ChargeLab, EV Connect, GreenFlux, Virta, Monta, Shell Recharge Solutions, ChargePoint, and Wallbox Business (the category leaders).

**Open-source emphasis**: The open-source ecosystem for EV charging is **maturing rapidly**. **SteVe** is the most established open-source OCPP server, developed at RWTH Aachen University since 2013 with over 1,000 GitHub stars . **EVerest**, backed by the Linux Foundation, is an open-source firmware stack for charging stations supporting OCPP 1.6, 2.0.1, and ISO 15118 . **CitrineOS** is an LF Energy project built on OCPP 2.0.1, adding OCPP 1.6 support in 2025 . This section focuses on these self-hostable, production-grade solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[AMPECO](https://www.ampeco.com/)**
  Bulgarian charging management platform. Selected by E.ON Drive Infrastructure in September 2024 as its charging management platform provider to manage over 6,000 public chargers across 11 countries . Provides full CPMS functionality including charging station management, payments, roaming, and smart charging.

- **[Driivz](https://driivz.com/)**
  Launched Platform V8 in November 2024 with network status dashboards, large-scale charger operations, energy management, and fleet-based reporting . Focuses on integrating operational workflows with energy workflows in enterprise deployments.

- **[ChargeLab](https://chargelab.co/)**
  Hardware-agnostic charging management software supporting OCPP-compliant charging stations. Provides monitoring, management, and optimization tools for charge point operators.

- **[EV Connect](https://www.evconnect.com/)**
  Charging station management platform with 2.61% market share in 2025 ($90 million). Provides charging network operations, driver support, and fleet management capabilities.

- **[GreenFlux](https://www.greenflux.com/)**
  Dutch charging management platform (acquired by DKV Mobility). Provides CPMS, roaming, and smart charging solutions focused on the European market.

- **[Virta](https://www.virta.global/)**
  Finnish charging management platform. Provides charging station management, driver apps, and energy services focused on Nordic and European markets.

- **[Monta](https://monta.com/)**
  Danish charging platform serving charge point operators, businesses, and drivers. Provides charging station management, payments, home charging, and fleet solutions.

- **[Shell Recharge Solutions](https://shellrecharge.com/)**
  Shell's charging management platform (formerly NewMotion). Provides charging station management, roaming, and commercial charging solutions.

- **[ChargePoint](https://www.chargepoint.com/)**
  North America's largest charging network operator with 5.66% market share in 2025 ($195 million). Provides a complete charging management platform including station management, driver apps, and subscription services.

- **[Wallbox Business](https://wallbox.com/)**
  Commercial charging management solution from charging hardware manufacturer Wallbox. Provides station management, payments, and energy management capabilities.

## Open-Source GitHub Projects

### OCPP Servers & Charging Station Management Systems (CSMS)

- **[SteVe](https://github.com/steve-community/steve)**
  The most established open-source OCPP server implementation, developed at RWTH Aachen University since 2013. The name comes from the German *Steckdosenverwaltung* (socket management). Supports OCPP 1.2S, 1.2J, 1.5S, 1.5J, 1.6S, and 1.6J. Provides charging point management, user data, and RFID card management. Docker deployment supported. **Java, GPL-3.0**. 714 GitHub stars . Note: currently does not support the OCPP 1.6 Security Whitepaper, and public instances pose security risks .

- **[CitrineOS](https://github.com/citrineos/citrineos-core)**
  Open-source charging station management system under the LF Energy project, developed by S44 Energy and donated to LF Energy. **Built on OCPP 2.0.1**, with OCPP 1.6 support added in 2025 to extend compatibility with legacy chargers . Modular architecture with new dynamic UI, GraphQL support, and S3-compatible MinIO file storage . **TypeScript, Apache-2.0**.

- **[MaEVe](https://github.com/maeve-tech/maeve)**
  Experimental electric vehicle charging station management system (CSMS). **88 GitHub stars**, actively developed .

- **[Open e-Mobility (SAP Labs France)](https://github.com/sap-labs-france/ev-server)**
  Open-source charging station management backend server from SAP Labs France. Includes ev-dashboard (Angular frontend, 79 stars) and ev-mobile (React-Native mobile app, 48 stars). **TypeScript, 170 stars**.

- **[gregszalay/ocpp-csms](https://github.com/gregszalay/ocpp-csms)**
  Modern, scalable OCPP 2.0.1 charging station management system. **Go language**, 36 GitHub stars .

### Charging Station Firmware & Operating Systems

- **[EVerest](https://github.com/EVerest/EVerest)**
  Open-source EV charging station firmware stack backed by the Linux Foundation (LF Energy). Initiated by PIONIX GmbH in 2020, with **contributing organizations including ABB, Siemens, Tesla, Eaton, and NREL** . Supports everything from unmanaged AC home chargers to complex multi-EVSE public DC charging stations with battery and solar support. Supports OCPP 1.6, 2.0.1, and ISO 15118, providing standards-compliant, interoperable, and secure charging . **C++, Apache-2.0**.

- **[CIP.io Link](https://github.com/cip-io/cip-io-link)**
  Open-source, vendor-neutral local EV charging controller developed by Argonne National Laboratory (ANL). Supports OCPP 1.6J with real-time dashboard, load balancing, and smart charging control. **Locally deployed with no cloud dependency**, reducing infrastructure and networking costs while providing full data ownership . **Open source**.

- **[Josev](https://github.com/josev-community/josev)**
  Community edition operating system for V2G charging stations. **129 GitHub stars**, supporting ISO 15118 communication protocol .

### OCPP Libraries & Tools

- **[Java-OCA-OCPP](https://github.com/ChargeTimeEU/Java-OCA-OCPP)**
  Open-source client and server library for the Open Charge Point Protocol (OCPP), as defined by the Open Charge Alliance. **353 GitHub stars**, actively maintained . **Java**.

- **[mobilityhouse/ocpp](https://github.com/mobilityhouse/ocpp)**
  Python implementation of the OCPP library. **997 GitHub stars**, the most popular OCPP implementation in the Python ecosystem .

- **[MicroOcpp](https://github.com/matth-x/MicroOcpp)**
  OCPP 1.6/2.0.1 client for microcontrollers. **509 GitHub stars**, suitable for embedded charger development .

- **[OCPP 2.0 Charge Point Simulator](https://github.com/ChargeTimeEU/OCPP-2.0-CP-Simulator)**
  OCPP 2.0 charge point simulator. **58 GitHub stars**, used for testing and development .

### Additional Strong Open-Source Options

- **OCPP Servers**: **SteVe** (most mature, GPL-3.0), **CitrineOS** (OCPP 2.0.1 + 1.6, Apache-2.0), **MaEVe** (experimental), **Open e-Mobility** (SAP Labs).
- **Charging Station Firmware**: **EVerest** (LF Energy, industry-backed), **CIP.io Link** (local control, no cloud dependency).
- **OCPP Libraries**: **Java-OCA-OCPP** (Java), **mobilityhouse/ocpp** (Python, 997 stars), **MicroOcpp** (embedded, 509 stars).
- **V2G/ISO 15118**: **Josev** (V2G operating system), **RISE-V2G** (ISO 15118 reference implementation).

**Frameworks for building custom systems**: Combine **SteVe** or **CitrineOS** as the OCPP server core, **EVerest** as charging station firmware, **mobilityhouse/ocpp** or **Java-OCA-OCPP** for protocol libraries, and **CIP.io Link** for local smart charging control. Add **PostgreSQL/MySQL** for persistence and **Docker** for deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- EV charging platforms handle sensitive payment and user data; ensure compliance with PCI DSS, GDPR, and relevant charging regulations.
- **Open-source reality**: The open-source ecosystem is mature and production-ready at the **OCPP server** level (SteVe, CitrineOS) and **charging station firmware** level (EVerest) . However, **full commercial CPMS functionality** (payment processing, roaming, driver apps, white-label portals) requires significant custom development. Commercial platforms (AMPECO, Driivz, ChargePoint) still dominate enterprise deployments.

---

**Made for charge point operators, fleet managers, energy companies, and EV infrastructure developers.**
Let's make EV charging management more open, interoperable, and scalable.
