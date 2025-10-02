# ABC Ltd End-to-End GRC (Portfolio) 🔒

This repository demonstrates a realistic, beginner-friendly Governance, Risk, and Compliance (GRC) workflow for **ABC Ltd**, a fictional **mid-sized retail company**.  
ABC Ltd handles **sensitive customer data** (payments, loyalty information, and employee records). Like many growing businesses, they face threats such as **payment fraud, insider misuse of data, and system downtime**.  

To address these challenges, this project follows a **structured GRC approach**

> 📈 **Flow:** Risk Register 📊 → Controls Mapping (NIST 800-53) 🛡️ → Policies 📚

---

## 🔗 Quick links
- 📂 **Risk Register:** [/risk](./risk)
- 📂 **Controls Mapping (NIST 800-53):** [/controls](./risk/controls)
- 📂 **Policies:** [/policies](./risk/controls/policies)

---

## 🧭 How to read this
1) **Start with the Risk Register 📊**  
   See how risks are **identified** (context + threats), **scored** (Likelihood × Impact), and **treated** (Mitigate / Transfer / Accept / Avoid).  
   File: `ABC-RiskRegister.xlsx` inside the `/risk` folder.

2) **Move to Controls Mapping 🛡️**  
   See which **NIST 800-53 control IDs** (e.g., `AC-2`, `AC-6`, `IA-2`) help reduce those risks.  
   File: `ABC_ControlsMapping.xlsx` inside the `/controls` folder.

3) **Open Policies 📚**  
   Short, business-friendly rules you can read right on GitHub. Policies may **mention Risk IDs** (e.g., `R-001`, `R-003`) for context; no per-risk mapping is required.
