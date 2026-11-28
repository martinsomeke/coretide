# Coretide: Platform Overview

> Building the technology your business runs on, and securing it from day one.

**Founder & Lead Engineer:** [Martins Omeke](https://github.com/martinsomeke) · 🌐 [coretide.io](https://coretide.io) · 𝕏 [@CoretideHQ](https://x.com/CoretideHQ)

This repository documents the design and security thinking behind CoreTide. Proprietary source code, client data and anything covered by NDAs are deliberately **not** included.

---

## 🌊 What Coretide does

CoreTide is a technology, infrastructure and cybersecurity company for organisations that need systems they can trust. The work spans three areas:

| Area | Focus |
|---|---|
| **Engineering** | Digital platforms and infrastructure built to operate, grow and last at scale |
| **Infrastructure & Security** | Software, cybersecurity, cloud and field execution, including custom-built workstations |
| **Products & Ventures** | Products built on a clear purpose and durable foundations |

---

## 🏗️ How it's built

| Layer | Approach |
|---|---|
| **Workspace backend** (what clients log into) | Engineered from scratch by Martins Omeke, with no third-party plugins. Every layer is owned and understood in-house. |
| **Marketing site** (coretide.io) | WordPress + Elementor: fast to update, so engineering time stays on the product |

---

## 🛡️ Coretide Console

The Console is CoreTide's security control centre. It's built around one idea: **every action on sensitive data must be justified, limited by policy, and recorded.**

### Core modules

| Module | Purpose |
|---|---|
| **Investigations** | Review suspicious or blocked activity in one place |
| **Agents** | Manage the people and automated agents that act on business systems |
| **Policies** | Define exactly what each agent may do, and under what scope |
| **Audit log** | A permanent record of every request, decision and outcome |

### Example: stopping data exfiltration by policy

A support agent requests a full customer data export. The request falls outside the scope of the ticket the agent is working on.

```
Request:   Customer data export
Agent:     Support agent
Policy:    Support access v3
Decision:  ❌ BLOCKED (outside ticket scope)
Exported:  0 records
Logged:    ✅ Audit log + Investigations
```

**Design principles behind this:**
- **Least privilege:** agents only get access tied to the task in front of them
- **Policy as the gatekeeper:** decisions come from versioned policies, not ad-hoc judgement
- **Deny by default:** anything outside scope is blocked, not just flagged
- **Full traceability:** every decision is auditable after the fact

---

## 🎓 CISE: Coretide Institute of Security Engineering

CISE is CoreTide's learning platform: structured courses and hands-on labs in cybersecurity.

**Sample lab: impossible travel detection**
An account signs in from **London** and then from **Bucharest** six minutes later. No one can travel that distance in that time, so the account is flagged for review. Learners work through the investigation the way a real security analyst would.

---

## ✅ Quality process

Every system CoreTide ships goes through **two human reviews** before release:

1. **System Review:** structure, performance and reliability
2. **Final Review:** consistency and the experience across every screen

---

## 📈 Results

- **Custom workstations:** CoreTide-built PCs stabilised an organisation's systems and **cut client complaints by 30%**
- **Business systems:** consolidated a client's scattered enquiries into a single system

*(Client names withheld. CoreTide honours every NDA it signs.)*

---

## 📫 Contact

- Business: **business@coretide.io**
- Founder: **prime@coretide.io**
