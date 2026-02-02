# Product Lifecycle & Engineering Governance Framework
**Technical Program Management | Zero-to-One Delivery | Reliability Engineering**

This repository serves as a technical portfolio documenting the frameworks I utilize to lead complex software and systems programs from initial discovery to high-availability production.

---

## 🚀 1. The "Zero-to-One" Discovery Phase
For startup and greenfield environments (AZ Enterprise / Spaan IT), I treat wireframes not just as design, but as a **Visual Project Plan**.

- **Tooling:** Maven / Wireframing tools.
- **Process:** We visualize every Android activity, button style, and click-flow (including payment link integration) to secure a stakeholder "All-Okay" before engineering begins.
- **Impact:** This "measure twice, cut once" approach eliminates mid-sprint pivots and ensures the development team is building a validated product.

---

## ⚖️ 2. The 8/80 Scope Governance Rule
To protect engineering velocity and prevent "Scope Creep," I implemented a 3-tier mathematical model for Change Requests (CRs) based on a 2-week sprint ($80\text{ Work Hours}$ per developer).

| Impact Tier | Threshold | Action Plan |
| :--- | :--- | :--- |
| **Tier 1: Minor** | $< 8\text{ WH}$ | Immediate implementation in current sprint. |
| **Tier 2: Major** | $8 - 80\text{ WH}$ | Planned for final stabilization sprint; budget adjusted. |
| **Tier 3: Strategic** | $> 80\text{ WH}$ | Re-scoped as a New Project Phase to protect stability. |

---

## 🛠️ 3. Engineering Workflow & Version Control
I bridge the gap between functional design and technical execution by integrating directly into the engineering workflow:
- **Collaboration:** Using **Git & Bitbucket** for code versioning and branch management.
- **Traceability:** Ensuring every code commit is mapped back to the validated "Visual Project Plan."
- **Agile Adaptability:** While wireframes are the starting point, the framework allows for "Agile Chopping" to respond to real-time customer feedback during development.

---

## 📉 4. Incident Management & Reliability (RAID/RCA)
In mission-critical infrastructure (Uisce Éireann / Cully Automation), I focus on decentralized accountability:
- **MS Planner Integration:** Migrated static RAID logs to dynamic, transparent boards.
- **RCA Culture:** Shifted incident logging ownership to the technical SCADA teams to facilitate **Root Cause Analysis (RCA)**.
- **Outcome:** Successfully restored data accuracy SLAs to **90%+ within six weeks**.

---
