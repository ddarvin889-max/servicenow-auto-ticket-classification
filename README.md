# Auto Ticket Classification Using ServiceNow

**Tamil Nadu Skill Development Corporation (TNSDC) – Naan Mudhalvan Scheme**

---

### 👥 Team Details
* **Team Id:**6ab6c394534c8646a9cdfba3
* **Project Title:** Auto Ticket Classification Using ServiceNow
* **Institution:** Government Arts and Science Collage ,Srivilliputhur.
* **Department:** Bsc.Computer Science
* **ServiceNow Instance ID:** dev396233

| S.No | Student Name | Role | Register / Roll Number |
|:---:|:---|:---|:---:|
| 1 | Anu Santhiya J | Team Leader | C4S44004 |
| 2 | Jenifer R | Team Member | C4s44006|
| 3 | Logadevi P | Team Member | C4s44007|
| 4 | Madhumitha M | Team Member | c4s44008 |

---

## 📌 Project Abstract
Incident Management is a core component of IT Service Management (ITSM). In organizations, handling numerous support tickets manually leads to response delays and inaccurate routing. 

This project implements **Automated Ticket Classification and Routing** in ServiceNow. Based on incoming incident attributes such as keywords in the short description, the system dynamically triages tickets and assigns them to the appropriate resolver groups without human intervention.

---

## ⚙️ Technology Stack
* **Platform:** ServiceNow Personal Developer Instance (PDI: dev396233)
* **Modules:** Incident Management, System Policy Rules
* **Key Components:** Assignment Rules, Condition Builders

---

## 🛠️ Implementation Steps

1. **Assignment Rule Configuration:**
   * Navigated to `System Policy > Rules > Assignment`.
   * Created a routing rule targeting the `incident` table.
   * Defined condition: `Short description contains VPN`.
2. **Automated Group Assignment:**
   * Configured the rule to automatically route matches to the `Network` assignment group.
3. **Execution & Verification:**
   * Created a test incident record with Short description `VPN Connection Issue`.
   * Validated that the incident automatically assigned to the Network team upon submission.

---

## 🎯 Conclusion
The project successfully automates ticket categorization and routing, significantly reducing Mean Time to Resolution (MTTR) and eliminating human error in ticket triage.
