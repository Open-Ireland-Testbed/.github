# Open Ireland Optical Testbed

[![CI](https://github.com/Open-Ireland-Testbed/twilight/actions/workflows/ci.yml/badge.svg)](https://github.com/Open-Ireland-Testbed/twilight/actions/workflows/ci.yml)

Welcome to the software stack powering Ireland’s national optical research infrastructure at Trinity College Dublin.

---

## Overview

The optical side of the **Open Ireland** is a programmable reconfigurable testbed built from Lumentum ROADMs, a 320 × 320 optical switch, In-line Juniper amplifiers, and coherent transponders. All devices expose open SDN APIs, allowing for experiments in optical transport and real‑time automation.

---

## Repository Index

| Repository | Visibility | Purpose | Main Language | License |
|------------|------------|---------|--------------|---------|
| [`tcdona3`](https://github.com/Open-Ireland-Testbed/tcdona3) | Public | Core control software for the optical testbed (device drivers, NETCONF APIs, automation scripts). | Python | MIT |
| [`twilight`](https://github.com/Open-Ireland-Testbed/twilight) | Private | Digital twin of the network. | Python | BSD-3-Clause |
| [`twinlink`](https://github.com/Open-Ireland-Testbed/twinlink) | Private | Real device behavior emulation for twilight over Netconf | C | - |
| [`twilight_integration`](https://github.com/Open-Ireland-Testbed/twilight_integration) | Private | External adapters and plug-ins for **twilight** (e.g., Kafka integration, TimescaleDB integration). | Python | BSD-3-Clause |
| [`twilight_mcp_integration`](https://github.com/Open-Ireland-Testbed/twilight_mcp_integration) | Private | Agent & MCP modules for natural language interactions. | Python | BSD-3-Clause |
| [`PDU_automation`](https://github.com/Open-Ireland-Testbed/PDU_automation) | Private | Scripts for remote power distribution unit control and energy telemetry. | Python | BSD-3-Clause |
| [`tcdona3_scheduler`](https://github.com/Open-Ireland-Testbed/tcdona3_scheduler) | Private | Equipment booking scheduler with REST API & CLI. | Python | MIT |

---

## Documentation & Resources

* **Wiki:** [https://open-ireland.atlassian.net/wiki/spaces/OP/overview](https://open-ireland.atlassian.net/wiki/spaces/OP/overview)
* **CONNECT Centre:** [https://connectcentre.ie](https://connectcentre.ie)

---

## Support

| Area                  | Contact                                                             |
| --------------------- | ------------------------------------------------------------------- |
| Lab PI       | Marco Ruffini — [marco.ruffini@tcd.ie](mailto:marco.ruffini@tcd.ie) |
| Admin  | Agastya Raj -  [rajag@tcd.ie](mailto:rajag@tcd.ie) |
| Admin  | Dmitrii Briantcev - [briantcd@tcd.ie](mailto:briantcd@tcd.ie) |

---

*Last updated: 25 June 2025*
