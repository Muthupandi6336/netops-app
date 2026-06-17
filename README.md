# NetOps Enterprise Platform

NetOps Enterprise is a high-performance Python and Streamlit automation platform designed to bridge network infrastructure management with real-time security auditing. It eliminates complex CLI overhead by introducing a centralized, reactive dashboard.

## 🚀 Core Pillars

* **Corporate IPAM Capacity Tracker:** Programmatic subnet management and safe OSPF routing.
* **Live Telemetry Monitors:** Tracks critical path latency, bandwidth deltas, and CRC input errors.
* **SecOps Compliance Engine:** Actively checks infrastructure design files against ISO 27001/CIS benchmarks, automatically identifying configuration drift and flagging insecure protocols like Telnet.

## 🛠️ Built With

* **Python** (Core Automation Logic)
* **Streamlit** (Reactive UI Framework)
* **YAML/JSON** (Compliance Pattern Mapping)
* **Bash/Shell** (Host Network Telemetry Parsing)

## 💻 Local Execution

1. Clone the repository using your secure SSH key:
   ```bash
   git clone git@github.com:Muthupandi6336/NetWatch-NOC.git

   ## 🎯 Why This Platform?

In modern enterprise infrastructures, network engineering and security compliance are often fragmented. Engineers spend valuable hours manually provisioning IP spaces via spreadsheets, configuring routing via legacy CLIs, and running separate security audits. This manual overhead creates configuration drift and introduces human error.

**NetOps Enterprise** bridges this gap by unifying configuration pipelines, live infrastructure telemetry, and automated compliance into a single reactive dashboard—turning manual operations into a programmatic, automated source of truth.

## 💼 Enterprise Benefits for Engineering Teams

Deploying this platform delivers massive operational advantages for network and SecOps teams:

* **Eliminates Configuration Drift:** Automatically validates live infrastructure setups against industry-standard frameworks (ISO 27001/CIS Benchmarks), stopping vulnerabilities before they hit production.
* **Proactive Risk Mitigation:** Instantly flags insecure, legacy plaintext protocols (like Telnet) and surfaces them on a centralized security feed.
* **Efficient IPAM & Automated Provisioning:** The corporate IPAM tracker prevents subnet overlapping, calculates host lease metrics dynamically, and ensures safe OSPF routing without messy manual calculations.
* **Reduced MTTR (Mean Time to Resolution):** By streaming live telemetry metrics (like CRC input errors, buffer queues, and path latency deltas) directly to the UI, teams can spot and troubleshoot network degradation instantly.
* **Zero CLI Overhead:** Replaces error-prone, manual command-line execution with a secure, centralized dashboard, reducing human error by automating state changes.
