# Hi, I'm Zavier 👋

Welcome to my cybersecurity portfolio! I am an analytical and hands-on ** Aspiring Cybersecurity Analyst**.

I utilize a dedicated, dual-station homelab environment to simulate real-world enterprise infrastructure, replicate corporate workflows, and analyze modern attack surfaces.

---

## 🛠️ My Enterprise Homelab Architecture

Instead of running heavy virtualization on my primary analyst workstation, I isolate all computing to a dedicated hypervisor node to maintain network integrity and performance.

* **Analyst Workstation:** ASUS ZenBook 14 OLED *(Documentation, cloud tenant governance, query building)*
* **Compute Node (Hypervisor):** HP ProDesk (Intel i5-9500, 32GB DDR4 RAM, 500GB NVMe SSD)
* **Network Foundation:** Dedicated physical Wired Ethernet connection for stable virtual switch routing.

---

## 🚀 Active Project Roadmap & Portfolio

I am progressively building a structured, enterprise-grade lab environment. You can explore the detailed triage reports, configuration baselines, and architecture maps in the folders above:

### 📁 Phase 1: Quick Wins & Operational Foundations
1. **Phishing Analysis (`/01-Phishing-Analysis`)** :white_check_mark:
   * Extracting indicators of compromise (IOCs) and tracing spoofed sender IPs from live samples using PhishTank, MXToolbox, and VirusTotal to generate executive triage reports.
2. **Open-Source IT Ticketing System (`/02-IT-Ticketing-osTicket`)**
   * Deploying osTicket on Linux to build support queues, map multi-tier SLA response matrices, and manage the full user-request lifecycle.

### 📁 Phase 2: On-Premises Infrastructure & Administration
3. **Windows Server On-Premises Active Directory Home Lab (`/03-Active-Directory-OnPrem`)**
   * Deploying a primary Domain Controller (.local forest), configuring DHCP/DNS scopes, structuring realistic corporate OUs, and pushing security baselines via Group Policy Objects (GPOs) to corporate clients.

### 📁 Phase 3: Defensive Monitoring & Threat Detection
4. **SIEM Detection Lab (`/04-Wazuh-SIEM-Detection`)**
   * Deploying a centralized Wazuh SIEM monitor on Linux linked via Sysmon to Windows endpoints. Simulating red team attacks (PowerShell exploits, privilege escalations) and writing custom alert rules.

### 📁 Phase 4: Modern Cloud & Enterprise Governance
5. **Identity & Access Management / Zero Trust Capstone (`/05-Entra-ID-Zero-Trust`)**
   * Engineering a Microsoft Entra ID cloud developer tenant with contextual Conditional Access Policies (MFA gates, geo-blocking, legacy auth blocks), detailed RBAC permission matrices, and automated Joiner-Mover-Leaver (JML) user lifecycle workflows.

---

## 🧰 Tech Stack & Tools Experienced

| Category | Tools & Technologies |
| --- | --- |
| **SIEM & Monitoring** | Wazuh, Microsoft Sysmon, Log Analysis |
| **Identity & Access** | Microsoft Entra ID (Azure AD), On-Prem Active Directory, GPOs, RBAC |
| **Threat Intelligence** | VirusTotal, MXToolbox, PhishTank |
| **Virtualization & OS**| VMware Workstation Pro, Ubuntu Server, Windows Server, Windows 10/11 Enterprise |
| **IT Operations** | osTicket, Ticketing Lifecycle, SLA Management |

---

## 📬 Connect With Me

* **Email:** zavieruddin@gmail.com
