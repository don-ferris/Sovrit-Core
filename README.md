# SovrIT Core  
**Runtime Substrate for the SovrIT Ecosystem**

SovrIT Core is the sovereign execution environment that all SovrIT modules run on. It is not a single service — it is the totality of the networking, resilience, storage, hardening, and operational foundations that make SovrIT a reliable, long‑lived personal IT platform.

Where the [**SovrIT Platform**](https://github.com/don-ferris/SovrIT)
 defines the philosophy and [architecture](https://github.com/don-ferris/SovrIT/blob/main/Architecture.md), SovrIT Core implements it.

---

## 🧩 Purpose

SovrIT Core exists to provide:

- a secure, encrypted networking fabric  
- a resilient, self‑healing infrastructure  
- a hardened, monitored runtime environment  
- a consistent operational foundation for all SovrIT modules  
- a human‑operable system that a non‑technical spouse/partner can manage with confidence  

Core is what transforms SovrIT from “self‑hosting” into sovereign personal infrastructure.

---

## 🧱 Components of SovrIT Core

### **1. SovrIT SecureNet**  
The encrypted overlay network and sovereign VPN that all SovrIT traffic flows through.

SecureNet provides:

- encrypted peer‑to‑peer overlay  
- sovereign remote access  
- device identity and routing  
- mobile device protection  
- WAN‑agnostic connectivity  

---

### **2. SovrIT Fortitude**  
The resilience engine of SovrIT.

Fortitude provides:

- backups  
- disaster recovery  
- monitoring  
- alerting  
- self‑healing  
- anti‑fragility  
- hardware redundancy (RAIDZ, UPS, failover WAN, redundant compute)  
- high‑availability patterns  

---

### **3. Provisioning & Hardening**

Core includes the patterns and tooling for:

- initial bootstrap  
- secure configuration  
- patching  
- incremental hardening  
- audit and compliance  
- lifecycle management  

---

### **4. Encrypted Storage Foundations**

Core defines the storage architecture:

- ZFS datasets  
- snapshots  
- replication  
- encryption at rest  
- dataset layout for SovrIT modules  

---

### **5. LLM‑Guided Operations**

SovrIT Core includes the operational layer that makes the system usable by anyone in the household:

- guided troubleshooting  
- contextual explanations  
- annotated procedures  
- runbook awareness  
- household operability  

---

## 🧩 How SovrIT Core Relates to SovrIT Modules

SovrIT Core provides the substrate.  
SovrIT Modules provide the services.

Modules depend on Core for:

- networking  
- storage  
- resilience  
- security  
- documentation  
- operability  

Core is the foundation.  
Modules are the building blocks.  
Integrations are optional extensions.

---

## 📐 Design Principles

- sovereignty first  
- infrastructure‑grade reliability  
- defense in depth  
- idempotent provisioning  
- human‑centered operability  
- longevity and maintainability  

---

## 📦 Repository Structure (recommended)

    sovrit-core/
    │
    ├── securenet/                 # SovrIT SecureNet (overlay + VPN)
    │   ├── config/
    │   ├── policies/
    │   └── bootstrap/
    │
    ├── fortitude/                 # SovrIT Fortitude (resilience engine)
    │   ├── backups/
    │   ├── disaster-recovery/
    │   ├── monitoring/
    │   ├── self-healing/
    │   └── hardware-redundancy/   # RAIDZ, UPS, failover WAN, redundant compute
    │
    ├── storage/                   # Encrypted storage foundations
    │   ├── zfs/
    │   ├── snapshots/
    │   └── replication/
    │
    ├── hardening/                 # Security posture + patching
    │   ├── audit/
    │   ├── patching/
    │   └── threat-models/
    │
    ├── provisioning/              # Bootstrap + lifecycle management
    │   ├── ansible/
    │   ├── terraform/
    │   └── inventory/
    │
    ├── llm-ops/                   # LLM-guided maintenance
    │   ├── prompts/
    │   ├── troubleshooting/
    │   └── workflows/
    │
    └── docs/                      # Human-facing documentation
        ├── binder/
        ├── runbooks/
        └── diagrams/

---

## 📜 License

SovrIT Core is released under the MIT License. See `LICENSE` for details.
