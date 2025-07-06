# Modular NAC Architecture, NAS Management and Hotspot/Captive Portal Architectural Design

## Overview

This repository presents a modular architecture for designing scalable, agentless Network Access Control (NAC) systems using FreeRADIUS as the core authentication engine. The approach is structured to separate authentication, authorization, and policy enforcement into composable components that can be independently developed, tested, and extended.

The design focuses on achieving:

- **Agentless Device Posture Assessment:** Integrating SNMP, ARP, OUI lookups, and active scanning for comprehensive visibility.
- **Policy-Driven Authentication:** Modular policies mapped to specific RADIUS virtual servers and context-aware decision trees.
- **System Resilience:** Separation of concerns across modules to minimize operational coupling and reduce failure domains.
- **Ease of Operational Adoption:** Clear configuration boundaries and reference implementations that can be adapted to heterogeneous environments.

This project is an abstraction of the NAC designs I have developed in production environments. All intellectual property in this repository is my own work or derived from public FreeRADIUS documentation and practices.

---

## Key Components

- **Modular Policy Framework:** Defines reusable policy units to assign VLANs, dynamic ACLs, and RADIUS attributes without hardcoding logic.
- **Dynamic Discovery Pipelines:** Passive and active discovery modules feeding posture and presence data into policy decisions.
- **Proof of Concept Configurations:** Example FreeRADIUS virtual servers, policy snippets, and workflow documentation.

---

## Intended Audience

- Security Architects designing zero-trust or NAC systems
- Network Engineers seeking to modernize legacy RADIUS infrastructures
- Researchers exploring agentless device identification and posture validation
- Developers building integrations with FreeRADIUS and network discovery tools

---

## License

This repository is published under the MIT License. You are free to use, adapt, and build upon the concepts and examples herein.

---

## About the Author

I am a systems architect with a focus on network access control, agentless device discovery, and security automation. My work emphasizes clarity, composability, and evidence-based trust decisions.

### Executive Summary

Systems Architect with deep expertise in designing modular, agentless Network Access Control solutions and zero-trust
authentication architectures. I have delivered end-to-end designs for high-availability NAC systems integrating RADIUS,
SNMP, NetFlow, automated posture assessment pipelines and many more. My work focuses on translating complex security
requirements into scalable frameworks that can be executed by teams without sacrificing clarity or resilience.
I specialize in:
- Modular policy-based authentication design
- Agentless and passive device discovery
- R&D prototyping and proof of concept development
- Strategic documentation and systems road mapping
I am seeking Principal Architect or R&D-focused roles where architectural rigor, research-driven innovation, and systemic
thinking are valued as core competencies.

For consulting inquiries or collaboration opportunities, please connect with me via [LinkedIn](https://www.linkedin.com/in/ege-bulut/) or [email](egebulut@hotmail.com).
