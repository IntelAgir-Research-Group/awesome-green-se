# Awesome Green SE

<img src="img/logo_awesome_greense.png" alt="Awesome Green SE logo" width="150"/>

A meeting point for making Software Engineering greener, with a list of tools, research, and useful websites. This initiative is led by academia researchers; however, industry collaborators are more than welcome. We aim to bridge research and industry to make software development more energy‑aware and environmentally friendly.

## General

- **Mission** – Promote sustainable software practices, reduce the carbon footprint of development pipelines, and share actionable knowledge.
- **Scope** – Covers design, coding, testing, CI/CD, cloud deployment, and other SE-related considerations.
- **Community** – Open to students, researchers, developers, DevOps engineers, and sustainability advocates/players.
- **Core Knowledge on Green SE** - We also keep a document as a starting point for knowledge on Green SE [here](https://www.overleaf.com/read/dmwsnqxnqnfx#9e583b). If you want to collaborate in writing the document, ask one of the mainteiners.

## Meet Us

- **Discord** – <https://discord.gg/green-se> (join `#general`, `#tool-talk`, `#research-share`)
- **LinkedIn profile** - We keep the community informed exclusivelly via LinkedIn. If you want to be an informed outsider, please, follow us there.
- **Virtual Meet‑ups** – XXX webinars on topics such as “Measuring Code Energy Use” and “Green CI/CD”. Recordings posted on the YouTube playlist: <https://youtube.com/playlist?list=XXX>
- **Annual Hackathon (online)** – “Green Code Sprint” (usually in XXX) to promote green software development. WDYT?

## Green Initiatives

- **Green PT**: GreenPT is a GPT-powered chat platform, and robust API, running on renewable energy and hosted in Europe for strict data protection.
- **Ecosia**: Ecosia is a Web Browser and Search Engine that uses its profits for the planet and produces enough renewable energy to power all searches twice over.

## Green Labs Around the Globe

TBA

## List of Books

| Title             | Authors       | Year | Notes                      |
| ----------------- | ------------- | ---- | -------------------------- |
| _Sustainable ..._ | Silva, et al. | 2022 | Introductory text with ... |

## List of Papers

### 2026

### 2025

### 2024

### 2023

### 2022

### 2021

### Older

- **“The Carbon...”** – _IEEE Software_, 2020. [link](#)

## List of Tools

### RAPL-based Software Profilers

| Category         | Tool             | Description                                                                             | Link                                                       |
| ---------------- | ---------------- | --------------------------------------------------------------------------------------- | ---------------------------------------------------------- |
| Energy Profiling | **CodeCarbon**   | Python library that logs energy use of scripts and notebooks.                           | [Link](https://github.com/mlco2/codecarbon)                |
| Energy Profiling | **Perf**         | Linux kernel-based performance and energy counter tool for CPU-level profiling.         | [Link](https://perf.wiki.kernel.org)                       |
| Energy Profiling | **Kepler**       | Kubernetes-based energy profiling tool that exposes power metrics via Prometheus.       | [Link](https://github.com/sustainable-computing-io/kepler) |
| Energy Profiling | **JoularCore**   | Java-based energy monitoring tool for measuring application-level power consumption.    | [Link](https://github.com/joular/joularcore)               |
| Energy Profiling | **EnergiBridge** | Cross-platform energy measurement library bridging hardware counters to software.       | [Link](https://github.com/tdurieux/EnergiBridge)           |
| Energy Profiling | **Smartwatts**   | Formula-based power model that estimates per-process energy use from hardware counters. | [Link](https://github.com/powerapi-ng/smartwatts-formula)  |
| Energy Profiling | **Scaphandre**   | Open-source energy monitoring agent for bare metal and virtualized environments.        | [Link](https://github.com/hubblo-org/scaphandre)           |
| Energy Profiling | **Powermetrics** | macOS-native tool for measuring CPU, GPU, and package power.                            | [Link](https://www.unix.com/man-page/osx/8/powermetrics)   |

### Hardware Power Meters

| Category                   | Tool                           | Description                                                                                                                                                                                                           | Link                                                                                                              |
| -------------------------- | ------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| Measurement Unit           | Monsoon                        | High-precision DC current/voltage measurement tool and standalone power supply for battery profiling.                                                                                                                 | [Link](https://www.msoon.com/high-voltage-power-monitor)                                                          |
| Smart Plug                 | Shelly Plug S                  | Wi-Fi smart plug with integrated power meter; supports Alexa, Google Assistant, MQTT, CoAP, and REST API.                                                                                                             | [Link](https://kb.shelly.cloud/knowledge-base/shelly-plug-s)                                                      |
| USB Meter                  | JoyIT-UM120                    | USB multimeter supporting voltage, current, and energy measurement with real-time graphs on display.                                                                                                                  | [Link](https://joy-it.net/en/products/JT-UM120)                                                                   |
| Measurement Unit           | Otii Arc Pro                   | Measures voltage/current for embedded systems energy optimization.                                                                                                                                                    | [Link](https://www.qoitech.com/otii-arc-pro/)                                                                     |
| PDU                        | Rittal Power Distribution Unit | Network-monitored rack PDU for real-time voltage, current, and power tracking in IT rack deployments.                                                                                                                 | [Link](https://www.rittal.com/com-en/products/PG0800ITINFRA1/PG7274ITINFRA1/PGR11260ITINFRA1)                     |
| Add on card (Dell only)    | iDRAC                          | Embedded controller in Dell PowerEdge servers for out-of-band power monitoring; tracks cumulative, peak, and average power consumption via web UI.                                                                    | [Link](https://www.dell.com/support/kbdoc/en-us/000391164/poweredge-how-to-monitor-server-health-from-the-idrac9) |
| Add on card (Multi-vendor) | IPMI                           | Vendor-neutral out-of-band interface for server power monitoring via `ipmitool`; works on most Intel and AMD server-class hardware from Dell, HP, Lenovo, Supermicro, and others. Not supported on ARM or FPGA nodes. | [Link](https://www.manageengine.com/network-monitoring/ipmi-monitoring.html)                                      |

# CONTRIBUTING

We welcome contributions from anyone interested in greener software. Please follow these steps:

1. **Fork the repository** and create a new branch.
2. **Add or update content** – ensure entries are verifiable (link to a paper, tool repo, or official documentation).
3. **Write a concise PR description** – include the source of each new entry.
4. **Submit the PR** – it will be reviewed by at least one maintainer within 7 days.

You can also collaborate by taking care of one of the open issues.

### Code of Conduct

All participants must adhere to the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/).

# MAINTEINERS

- **Michel Albonico** - UTFPR, Brazil/SDU, Denmark
- **Vincenzo Stoico** - VU Amsterdam, The Netherlands

# LICENSE

This repository is licensed under the **MIT License**. Contributions are automatically licensed under the same terms.

---

_Together we can make software development a greener, more sustainable practice._

---
