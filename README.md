# Stochastic Modeling of Service Capacity for Depressive Disorders in Tibet

## 🏥 Project Background & Motivation
**From Clinical Observation to Quantitative Modeling**

**During my experience accompanying patients to clinical visits, I observed a structural mismatch in healthcare resources for **depressive disorders** within hospitals in Tibet.**

This project is my attempt to quantify these observations. Using a **Stochastic Discrete-Event Simulation**, I modeled the patient journey to identify bottlenecks that traditional qualitative surveys might miss.

## 🧠 Author's Contribution & Workflow
As a prospective student transitioning from medicine to data science, this project reflects my current learning process:

* **Concept & Logic (My Core Contribution):**
    * Designed the "Dual-Node" structure based on local hospital interactions.
    * **Data Curation:** All simulation parameters (prevalence rates, service capacity, patient behavior) were manually researched and calibrated based on the *7th National Population Census*, *Lancet Psychiatry* papers, and my own clinical fieldwork notes.

* **Implementation (AI-Assisted):**
    * I utilized AI coding assistants to help translate my logical flow charts into executable `Python` code (`NumPy`, `Pandas`).
    * **While this workflow bridged my immediate gap in syntax, it also exposed my limitations in engineering robust code, reinforcing my determination to pursue systematic, in-depth learning in this field.**

## 🔍 Key Findings
* **The "Awareness Paradox":** Increasing public awareness without expanding the central hub's capacity leads to a system crash (>70% blockage), not better care.
* **Solution:** A diversion strategy utilizing general hospitals is statistically more effective than expanding the specialist center alone.

## 📂 Data Sources
All parameters are grounded in real-world evidence collected during my research:
* **Demographics:** 7th National Population Census (2021).
* **Epidemiology:** Huang et al. (2019).
* **Capacity Limits:** Official outpatient announcements from the **Second People's Hospital of the Tibet Autonomous Region**.

## ⚠️ Limitations
The current model represents a **static snapshot** of annual capacity. It does not yet incorporate **backlog feedback loops** (where rejected patients re-enter the queue the next day).

---
*Created by: [Your Name]*