# Etherisc SaaS

**The versatile Software-as-a-Service platform for financial applications**

## Platform Components

| Component | Purpose |
|-----------|---------|
| **Control Plane** | Tenant management, hardware provisioning, deployment orchestration |
| **Platform App** | End-user application runtime with modular architecture |
| **Platform SDK** | Shared types, standards, and configuration packages |

## Architecture

```
┌─────────────────────────────────────────────────────────┐
│                    Control Plane                         │
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────────┐  │
│  │     API     │  │     CLI     │  │   Provisioner   │  │
│  └─────────────┘  └─────────────┘  └─────────────────┘  │
└─────────────────────────────────────────────────────────┘
                          │
                          ▼
┌─────────────────────────────────────────────────────────┐
│                  Tenant Applications                     │
│  ┌─────────────────────────────────────────────────────┐│
│  │  Platform App + Modules (Insurance, ...)            ││
│  └─────────────────────────────────────────────────────┘│
└─────────────────────────────────────────────────────────┘
```

---

*Built with TypeScript, Express, React, and PostgreSQL*
