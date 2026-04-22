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
- **LinkedIn profile** - We will keep the community informed exclusivelly via LinkedIn (TBA). If you want to be an informed outsider, please, follow us there.
<!-- - **Virtual Meet‑ups** – XXX webinars on topics such as “Measuring Code Energy Use” and “Green CI/CD”. Recordings posted on the YouTube playlist: <https://youtube.com/playlist?list=XXX>
- **Annual Hackathon (online)** – “Green Code Sprint” (usually in XXX) to promote green software development. WDYT? -->

## Green Initiatives

- **Green PT**: [GreenPT](https://greenpt.ai/) is a GPT-powered chat platform, and robust API, running on renewable energy and hosted in Europe for strict data protection.
- **Ecosia**: [Ecosia](https://www.ecosia.org/) is a Web Browser and Search Engine that uses its profits for the planet and produces enough renewable energy to power all searches twice over.

## Green Labs Around the Globe

| Name                                       | Administrator/Responsible | Local                     | Web Page                                        |
| ------------------------------------------ | ------------------------- | ------------------------- | ----------------------------------------------- |
| GreenLab                                   | Vincenzo Stoicco          | S2 Group@VU Amsterdam, NL | [GitHub](https://github.com/S2-group/green-lab) |
| Sustainable Software Engineering (S2E) Lab | Michel Albonico           | SDU Vejle, DK             | [TBA](#)                                        |

## List of Tools

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

### Software Profilers

This list has been initially compiled in [this](https://arxiv.org/abs/2603.21772) study.

| URL                                                            | Repo Name                                 | Description                                                                                                                                                                                                                                                                                       |
| -------------------------------------------------------------- | ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <https://github.com/ColinIanKing/powerstat>                    | ColinIanKing/powerstat                    | Powerstat measures the power consumption of a machine using the battery stats or the Intel RAPL interface. The output is like vmstat but also shows power consumption statistics. At the end of a run, powerstat will calculate the average, standard deviation and min/max of the gathered data. |
| <https://github.com/powerapi-ng/pyRAPL>                        | powerapi-ng/pyRAPL                        | A library to measure the Python energy consumption of Python code.                                                                                                                                                                                                                                |
| <https://github.com/powerapi-ng/pyJoules>                      | powerapi-ng/pyJoules                      | A Python library to capture the energy consumption of code snippets.                                                                                                                                                                                                                              |
| <https://github.com/hubblo-org/scaphandre>                     | hubblo-org/scaphandre                     | ⚡ Energy consumption metrology agent. Let "scaph" dive and bring back the metrics that will help you make your systems and applications more sustainable!                                                                                                                                        |
| <https://github.com/mlco2/codecarbon>                          | mlco2/codecarbon                          | Track emissions from compute and recommend ways to reduce their impact on the environment.                                                                                                                                                                                                        |
| <https://github.com/trulyspinach/SMCAMDProcessor>              | trulyspinach/SMCAMDProcessor              | Power management, monitoring, and VirtualSMC plugin for AMD processors.                                                                                                                                                                                                                           |
| <https://github.com/saintslab/carbontracker>                   | saintslab/carbontracker                   | Track and predict the energy consumption and carbon footprint of training deep learning models.                                                                                                                                                                                                   |
| <https://github.com/enp1s0/gpu_monitor>                        | enp1s0/gpu_monitor                        | Records GPU temperature, power consumption, and memory usage while executing programs on GPUs.                                                                                                                                                                                                    |
| <https://github.com/joular/powerjoular>                        | joular/powerjoular                        | PowerJoular allows monitoring power consumption of multiple platforms and processes.                                                                                                                                                                                                              |
| <https://github.com/joular/joularjx>                           | joular/joularjx                           | JoularJX is a Java-based agent for software power monitoring at the source code level on all OSes.                                                                                                                                                                                                |
| <https://github.com/sustainable-computing-io/kepler>           | sustainable-computing-io/kepler           | Kepler (Kubernetes-based Efficient Power Level Exporter) is a Prometheus exporter that measures energy consumption metrics at the container, pod, and node levels in Kubernetes clusters.                                                                                                         |
| <https://github.com/ml-energy/zeus>                            | ml-energy/zeus                            | Measure and optimize the energy consumption of your AI applications!                                                                                                                                                                                                                              |
| <https://github.com/sb-ai-lab/Eco2AI>                          | sb-ai-lab/Eco2AI                          | eco2AI is a Python library that accumulates statistics about power consumption and CO2 emission during running code.                                                                                                                                                                              |
| <https://github.com/green-coding-solutions/green-metrics-tool> | green-coding-solutions/green-metrics-tool | Measure energy consumption and carbon emissions of software - timelines, git integration, comparisons, dashboards, and optimizations included.                                                                                                                                                    |
| <https://github.com/fvaleye/tracarbon>                         | fvaleye/tracarbon                         | 🌍 Tracarbon tracks your device's energy consumption and calculates your carbon emissions using your location.                                                                                                                                                                                    |
| <https://github.com/graelo/pumas>                              | graelo/pumas                              | Power Usage Monitor for Apple Silicon.                                                                                                                                                                                                                                                            |
| <https://github.com/Root-Branch/cardamon-core>                 | Root-Branch/cardamon-core                 | 🌱 A tool for measuring the power consumption and carbon footprint of your software.                                                                                                                                                                                                              |
| <https://github.com/tdurieux/EnergiBridge>                     | tdurieux/EnergiBridge                     | Energibridge is a cross-platform energy measurement utility that provides support for Linux, Windows, and macOS, as well as Intel, AMD, and Apple ARM CPU architectures.                                                                                                                          |
| <https://github.com/maufadel/EnergyMeter>                      | maufadel/EnergyMeter                      | A Python tool to measure the energy consumption of software.                                                                                                                                                                                                                                      |
| <https://github.com/mlco2/ecologits>                           | mlco2/ecologits                           | 🌱 EcoLogits tracks the energy consumption and environmental footprint of using generative AI models through APIs.                                                                                                                                                                                |
| <https://github.com/wattwisegames/watt-wiser>                  | wattwisegames/watt-wiser                  | Tools to measure and visualize energy use on desktop computers.                                                                                                                                                                                                                                   |
| <https://github.com/FairCompute/energy-monitoring-tool>        | FairCompute/energy-monitoring-tool        | Enabling digital sustainability through granular energy measurement.                                                                                                                                                                                                                              |
| <https://github.com/superdango/cloud-carbon-exporter>          | superdango/cloud-carbon-exporter          | Estimates energy consumption and CO2 emissions of your cloud resources in real time.                                                                                                                                                                                                              |
| <https://github.com/NOVADEDOG/energy-leaderboard-runner>       | NOVADEDOG/energy-leaderboard-runner       | Open-source energy benchmark for local LLMs. Measures Wh and CO2 using real hardware sensors (RAPL, NVML, powermetrics).                                                                                                                                                                          |
| <https://github.com/jordond/jolt>                              | jordond/jolt                              | ⚡️ A terminal-based battery and energy monitor for macOS and Linux.                                                                                                                                                                                                                              |
| <https://github.com/alumet-dev/alumet>                         | alumet-dev/alumet                         | Next-gen monitoring tool with high-frequency energy measurement                                                                                                                                                                                                                                   |

## Literature

### List of Books

| Title                                                                                    | Authors/Editors                          | Year | Notes                                                             |
| ---------------------------------------------------------------------------------------- | ---------------------------------------- | ---- | ----------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| _Building Green Software: A Sustainable Approach to Software Development and Operations_ | Anne Currie, Sarah Hsu, and Sara Bergman | 2024 | Techniques and metrics in the green software development process. | [LINK](https://www.amazon.com/Building-Green-Software-Sustainable-Development/dp/1098150627) |
| _Green in Software Engineering_                                                          | Coral Calero, and Mario Piattini         | 2016 | Fundamentals of Green Software Engineering.                       | [LINK](https://www.amazon.com/Green-Software-Engineering-Coral-Calero/dp/3319361090)         |

### Other Sources

| **Source**                                                      | **Description**                                                                                                                                                              | **Link**                                                                                                                                         |
| --------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| _Green Software Foundation_                                     | **Website** of the best-known non-profit foundation aimed at building a trusted ecosystem of people, standards, tools, and best practices for creating sustainable software. | [LINK](https://greensoftware.foundation/)                                                                                                        |
| _GreenIT on a Cloud_                                            | **Podcast** about successful sustainability cases in information technology environments.                                                                                    | [LINK](https://open.spotify.com/show/1oSqlKOSOf9W4cELSoUewS)                                                                                     |
| _Sustainable Software Engineering_                              | **Course** covering the main topics related to Green Software Engineering.                                                                                                   | [PDF](https://learn.microsoft.com/en-us/training/modules/sustainable-software-engineering-overview/)                                             |
| _Making software and data architectures more sustainable_       | **Online article** about making software and data structures more sustainable.                                                                                               | [LINK](https://www.mckinsey.com/capabilities/mckinsey-digital/our-insights/tech-forward/making-software-and-data-architectures-more-sustainable) |
| _Green Software Engineering -- Developer Guide_                 | **Guide** on Green Software Engineering issues for software developers.                                                                                                      | [LINK](https://fuller.com.au/wp-content/uploads/2023/02/Green-Software-Engineering-Full-Guide-Feb-2023-Fuller-Brand-Communication.pdf)           |
| _Green Software Engineering Done Right_                         | **Online article** with guidance on how researchers can organize experiments in energy efficiency.                                                                           | [LINK](https://luiscruz.github.io/2021/10/10/scientific-guide.html)                                                                              |
| _Measuring the Emissions -- Energy Footprint of the ICT Sector_ | **World Bank report** about energy consumption and greenhouse gas emissions worldwide.                                                                                       | [LINK](https://documents1.worldbank.org/curated/en/099121223165540890/pdf/P17859712a98880541a4b71d57876048abb.pdf)                               |

### Academic Papers

#### 2026

- Cannizza, M. B., & Albonico, M. (2026). **A Curated List of Open-source Software-only Energy Efficiency Measurement Tools: A GitHub Mining Study**. Accepted at GreenArch Workshop@ICSA [PDF](https://arxiv.org/pdf/2603.21772)
- Mehditabar, Mohammadjavad, Saurabhsingh Rajput, and Tushar Sharma. "A Validated Taxonomy on Software Energy Smells.", [PDF](https://arxiv.org/pdf/2604.04809)
- Solovyeva, L. and Castor, F., 2026. Towards Green AI: Decoding the Energy of LLM Inference in Software Development [PDF](https://arxiv.org/pdf/2602.05712)

#### 2025

Stoico, V., Dragomir A. C., and Lago P.. "An empirical study on the performance and energy usage of compiled python code." In Proceedings of the 29th International Conference on Evaluation and Assessment in Software Engineering, [PDF](https://dl.acm.org/doi/pdf/10.1145/3756681.3756972)

- Apsan, Radu, Vincenzo Stoico, Michel Albonico, Rudra Dhar, Karthik Vaidhyanathan, and Ivano Malavolta. "Generating Energy-Efficient Code via Large-Language Models--Where are we now?.", [PDF](https://arxiv.org/pdf/2509.10099?)

- Lago, Patricia, and Ivano Malavolta. "A New Vision on Software Sustainability and Its Engineering." IEEE Software 43, [PDF](https://ieeexplore.ieee.org/iel8/52/11316879/11316890.pdf?casa_token=fM9OxXXP_ycAAAAA:Gk8eU2Zt1jnLbxjULkE8Cb4YLfXFdjcGl-7PC0VEPS9A1zMwss4IFDgnLa_nYsOJ3C1agPMQFbMQLw)

- Poenaru-Olaru, L., Sallou, J., Cruz, L., Rellermeyer, J., & van Deursen, A. (2025). **Sustainable Machine Learning Retraining: Optimizing Energy Efficiency Without Compromising Accuracy**. arXiv preprint arXiv:2506.13838. [PDF](https://drive.google.com/file/d/1uFizKXssrtm2eLDhA1cn2H7zf2lrS8xk/view?usp=sharing)

- Christensen, H. B., Kirkeby, M. H., Thomsen, B., & Thomsen, L. L. (2025). **Teaching Energy-Efficient Software--An Experience Report**. arXiv preprint arXiv:2504.19707. [PDF](https://drive.google.com/file/d/1AWakwMdjqndOk87s_7Ym_KO5940o9_rU/view?usp=sharing)

- Conrardy, A., Sulejmani, A., Guerlain, C., Pagani, D., Hick, D., Satta, M., & Cabot, J. (2025). **Low-code to fight climate change: the Climaborough project**. arXiv preprint arXiv:2506.14623. [PDF](https://drive.google.com/file/d/1I4XfVyv7oXxu9mSs0ajhQjJvHwBub_Ez/view?usp=sharing)

- Maquoi, J., Cauz, M., Vanderose, B., & Devroey, X. (2025, June). **Energy Codesumption, Leveraging Test Execution for Source Code Energy Consumption Analysis**. In 33rd ACM International Conference on the Foundations of Software Engineering. ACM Press. [PDF](https://drive.google.com/file/d/1RlwV0YzUF0IvUTjBcJSDjMSFByYr9Dsw/view?usp=sharing)

- Verdecchia, R., Cruciani, E., Bertolino, A., & Miranda, B. (2025, April). **Energy-Aware Software Testing**. In 2025 IEEE/ACM 47th International Conference on Software Engineering: New Ideas and Emerging Results (ICSE-NIER) (pp. 101-105). IEEE. [PDF](https://drive.google.com/file/d/1OZ7GbZw6JzSBYN1zAU-ja891og-fi_oK/view?usp=sharing)

- Solovyeva, L., Weidmann, S., & Castor, F. (2025). **AI-Powered, But Power-Hungry? Energy Efficiency of LLM-Generated Code**. arXiv preprint arXiv:2502.02412. [PDF](https://drive.google.com/file/d/1wt7VxQw-HdkdWw_5Rh6X0Q2CkU5BQpVR/view?usp=sharing)

- van Kempen, N., Kwon, H.J., Nguyen, D.T. and Berger, E.D., 2025, November. It’s not easy being green: On the energy efficiency of programming languages. In 2025 40th IEEE/ACM International Conference on Automated Software Engineering (ASE) (pp. 1553-1565), [PDF](https://ieeexplore.ieee.org/iel8/11334056/11334198/11334459.pdf?casa_token=t08I-fNWuZ8AAAAA:G2e3BTtrOYyF5DlCha8wEUVbXFKH2W7PFcLcoGdKQ1A_2w3ypDr3D48y5OmVDeB_O851_vQH4iwi0A)

#### 2024

- Alizadeh, N., & Castor, F. (2024, April). **Green AI: A Preliminary Empirical Study on Energy Consumption in DL Models Across Different Runtime Infrastructures**. In Proceedings of the IEEE/ACM 3rd International Conference on AI Engineering-Software Engineering for AI (pp. 134-139). [PDF](https://drive.google.com/file/d/15oCpN6n0rGM8peiHjlvxztCyzTPqfUIX/view?usp=sharing)

- Castor, F. (2024). **Estimating the Energy Footprint of Software Systems: a Primer**. arXiv preprint arXiv:2407.11611. [PDF](https://drive.google.com/file/d/1PU6qGX_SeSDfB340c2yLCpBTItspm3ta/view?usp=sharing)

- Malavolta, I., Stoico, V., & Lago, P. (2024). **Ten Years of Teaching Empirical Software Engineering in the Context of Energy-Efficient Software**. In Handbook on Teaching Empirical Software Engineering (pp. 209-253). Cham: Springer Nature Switzerland. [PDF](https://drive.google.com/file/d/1Qon0oaWiPbfUhSjRiDXipqIfubRNKUWm/view?usp=sharing)

- Balanza-Martinez, J., Lago, P., & Verdecchia, R. (2024). **Tactics for software energy efficiency: a review**. In Environmental Informatics (pp. 115-140). Springer, Cham. [PDF](https://drive.google.com/file/d/1y8OJHf9_Jh_Ht7sByuK-uqMcGAUcRrC2/view?usp=sharing)

#### 2023

- Stoico, V., Cortellessa, V., Malavolta, I., Di Pompeo, D., Pomante, L., & Lago, P. (2023, June). **An approach using performance models for supporting energy analysis of software systems**. In European Workshop on Performance Engineering (pp. 249-263). Cham: Springer Nature Switzerland. [PDF](https://drive.google.com/file/d/1P6j5L8LdZLhOPwEvxXq9lwim58sGrkp3/view?usp=sharing)

#### 2022

- Noureddine, A. (2022, June). **Powerjoular and joularjx: Multi-platform software power monitoring tools**. In 2022 18th International Conference on Intelligent Environments (IE) (pp. 1-4). IEEE. [PDF](https://drive.google.com/file/d/1d7EQINwiyAZkiWYUhN0HrExAyfNMZmQo/view?usp=sharing)

- Vos, S., Lago, P., Verdecchia, R., & Heitlager, I. (2022, June). **Architectural tactics to optimize software for energy efficiency in the public cloud**. In 2022 International Conference on ICT for Sustainability (ICT4S) (pp. 77-87). IEEE. [PDF](https://drive.google.com/file/d/1GiicgOT3J6HsAF6cGVmzX4cqTCpblzlT/view?usp=sharing)

#### 2021

- Pereira, R., Couto, M., Ribeiro, F., Rua, R., Cunha, J., Fernandes, J. P., & Saraiva, J. (2021). **Ranking programming languages by energy efficiency**. Science of Computer Programming, 205, 102609. [PDF](https://drive.google.com/file/d/16slGmoEv2Hsg9s3FvKE12o6pFfUzeTe9/view?usp=sharing)

- Verdecchia, R., Lago, P., Ebert, C., & De Vries, C. (2021). **Green IT and green software**. IEEE Software, 38(6), 7-15. [PDF](https://drive.google.com/file/d/1sbLFYm06mJRzUg8oDUR4eu5wp-WcIyA-/view?usp=sharing)

#### 2020

- Couto, M., Maia, D., Saraiva, J., & Pereira, R. (2020, June). **On energy debt: managing consumption on evolving software**. In Proceedings of the 3rd International Conference on Technical Debt (pp. 62-66). [PDF](https://drive.google.com/file/d/1M-poWUVdzPYK87VsDr81wmgHAjbOvKJB/view?usp=sharing)

#### Older

- Fonseca, A., Kazman, R., & Lago, P. (2019). **A manifesto for energy-aware software**. IEEE Software, 36(6), 79-82. [PDF](https://drive.google.com/file/d/1wrmUb8JZEI017xbnNl3ceS_Mbgo_g4bf/view?usp=sharing)

- Verdecchia, R., Procaccianti, G., & Lago, P. (2018). **Empirical evaluation of the energy impact of refactoring code smells**. In 5th International Conference on Information and Communication Technology for Sustainability. ICT4S2018 (pp. 365-383). EasyChair. [PDF](https://drive.google.com/file/d/1wn_e5kTz-85fWV2h-OtZdhsBu1n-oD10/view?usp=sharing)

- Pinto, G., & Castor, F. (2017). **Energy efficiency: a new concern for application software developers**. Communications of the ACM, 60(12), 68-75. [PDF](https://drive.google.com/file/d/1gdgfNSWDxmMBdHUho-8RjLXAnEdKYYJU/view?usp=sharing)

- Noureddine, A., Rouvoy, R., & Seinturier, L. (2013). **A review of energy measurement approaches**. ACM SIGOPS Operating Systems Review, 47(3), 42-49. [PDF](https://drive.google.com/file/d/1NF-cFS2Q-3u07t0iq-ekju028mgG6bt2/view?usp=sharing)

## Considerações

A escrita deste documento foi melhorada e auxiliada por ferramentas LLM, como o ChatGPT. Todo o conteúdo foi organizado pelo professor da disciplina, quem também validou a versão final do documento.

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
