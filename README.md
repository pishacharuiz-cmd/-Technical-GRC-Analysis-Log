 Technical GRC Analysis Log

## Introduction
This repository serves as a record of my hands-on technical training, designed to bridge the gap between security operations and GRC policy architecture. My primary goal is to develop a deep, practical understanding of security controls by executing them in a lab environment, and subsequently critiquing their real-world efficacy from a risk and continuity perspective.

---

## Module 1: Blue Team Introduction
**Status**: ✅ Completed

### Key Takeaways & Observations
*   **Operational Ecosystem:** Successfully mapped the collaborative security ecosystem, identifying the distinct roles of SOC Analysts, GRC Auditors, Threat Researchers, and Incident Responders.
*   **Policy Critique (Finding #001):** During the module, I analyzed a control policy requiring manual human approval for all server logons.
    *   **The Conflict:** While meeting a "check-the-box" compliance requirement, this creates a severe operational bottleneck.
    *   **BCP Impact:** This control acts as a single point of failure during a Business Continuity (BCP) event. If the approving authority is unavailable during a crisis, recovery time is significantly impacted.
    *   **Proposed Recommendation:** Replace manual approval with **Just-in-Time (JIT) access** or **risk-based conditional access policies**. These satisfy security requirements while maintaining organizational resilience and reducing Recovery Time Objectives (RTO).

---

## Next Steps
*   **Focus:** Moving into **SIEM and Log Analysis** modules.
*   **Objective:** Continue investigating how automated, risk-based technical controls can effectively replace flawed, manual operational processes.

---
*“I don't just want to know how to pass a test; I want to understand how to design controls that actually protect the business without hindering it.”*
