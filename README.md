# Cyber-Physical Engineering

**Cybersecurity compliance for regulated industries.**

We build open-source tools for **trust assurance**—security monitoring, access control, auditability, and verifiable provenance around regulated data and critical systems.

---

## Our Stack

| Layer | Tool | What It Does |
|-------|------|-------------|
| **Business** | [healthsec_trust_calculator](https://github.com/BigDataPlumbing/healthsec_trust_calculator) | Calculate financial impact of trust assurance |
| **Assessment** | [healthsec_maturity_scorecard](https://github.com/BigDataPlumbing/healthsec_maturity_scorecard) | Score your compliance posture |
| **Ecosystem** | [health_ecosystem_trust_model](https://github.com/BigDataPlumbing/health_ecosystem_trust_model) | Economic trust modeling for US health ecosystem |
| **Architecture** | [opensource_truststack](https://github.com/BigDataPlumbing/opensource_truststack) | Reference implementation for trust assurance |
| **AI Gateway** | [clinical_ai_gateway](https://github.com/BigDataPlumbing/clinical_ai_gateway) | Policy-driven AI guardrails for HIPAA/FDA |
| **Device Layer** | [device_trust_shim](https://github.com/BigDataPlumbing/device_trust_shim) | Tamper-evident logging for embedded devices |
| **Crypto** | [secure_crate](https://github.com/BigDataPlumbing/secure_crate) | Enterprise-grade cryptographic engine (Rust) |

---

## Industries We Serve

- **Healthcare & Life Sciences** — HIPAA, FDA, GxP compliance
- **Manufacturing & Industrial** — CMMC, ISA/IEC 62443, OT security
- **Defense & Aerospace** — Air-gapped systems, secure supply chains
- **Building Automation** — KNX, BACnet, smart infrastructure

---

## Technology

Our tools span the full stack:

```
┌─────────────────────────────────────────────────────────────────────┐
│                          TRUST ASSURANCE                            │
├─────────────────────────────────────────────────────────────────────┤
│                                                                     │
│   Business Layer           Assessment Layer         Ecosystem       │
│  ┌─────────────────┐      ┌─────────────────┐    ┌──────────────┐  │
│  │ trust_calculator│      │maturity_scorecard│    │ trust_model  │  │
│  │    (Python)     │      │    (Python)      │    │ (TypeScript) │  │
│  └─────────────────┘      └─────────────────┘    └──────────────┘  │
│                                                                     │
├─────────────────────────────────────────────────────────────────────┤
│                                                                     │
│   Cloud Layer              Gateway Layer           Crypto Layer     │
│  ┌─────────────────┐      ┌─────────────────┐    ┌──────────────┐  │
│  │opensource_trust │      │clinical_ai_     │    │ secure_crate │  │
│  │stack (JavaScript)│      │gateway (Python) │    │   (Rust)     │  │
│  └─────────────────┘      └─────────────────┘    └──────────────┘  │
│                                                                     │
├─────────────────────────────────────────────────────────────────────┤
│                                                                     │
│                         Device Layer                                │
│                    ┌─────────────────────┐                          │
│                    │  device_trust_shim  │                          │
│                    │       (C++)         │                          │
│                    └─────────────────────┘                          │
│                                                                     │
│   Protocols: DICOM | Modbus | OPC UA | KNX | BACnet | EtherNet/IP  │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

---

**Trust nothing. Prove everything.**

[bigdataplumbing.com](https://www.bigdataplumbing.com) · [HealthSec Alliance](https://healthsecalliance.com)

