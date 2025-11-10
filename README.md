# 🧮 PEER Financial Agent  
### Automating Workflows and Enhancing Decision-Making in Financial Statement Analysis  

![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)  
![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)  
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)  
![AI](https://img.shields.io/badge/AI-Multi--Agent%20System-orange.svg)

---

## 📘 Overview  

The **PEER Financial Agent** project explores how **multi-agent AI systems** can automate and enhance financial statement analysis.  
It examines whether a team of specialized AI agents can outperform a single, monolithic AI model in producing accurate and actionable financial reports.

This repository contains research code, experimental results, and documentation for the PEER architecture — **Plan, Execute, Express, Report**.

---

## 🎯 Objectives  

- Automate **financial statement analysis** using an agentic AI architecture.  
- Compare **multi-agent** and **single-agent** designs for both quantitative and qualitative performance.  
- Evaluate how **code-execution tools** impact the reliability and depth of analysis.  

---

## 🧩 System Architecture  

### 1. **Baseline Model**  
A single, powerful AI performing the full analysis independently — no specialization or external tools.  

### 2. **PEER System** *(Plan → Execute → Express → Report)*  
A **multi-agent pipeline** where each agent handles a distinct phase of the workflow.  

### 3. **PEER_ablation**  
A simplified version of PEER **without code-execution tools**, isolating the effect of tool usage on results.

---

## 💼 Test Scenarios  

All three systems were tested on **four identical, synthetic financial scenarios** to ensure fairness and repeatability:  

| Scenario | Description |
|:--|:--|
| **Balance Sheet Analysis** | Evaluate company financial health and debt strategy. |
| **Performance Benchmarking** | Compare a company against industry peers. |
| **Ratio Analysis** | Track metrics through a volatile business cycle. |
| **Trend Analysis** | Examine strategic shifts in a high-growth software firm. |

---

## ⚖️ Evaluation Criteria  

An **automated AI referee** evaluated all reports using two key metrics:

1. **Numeric Accuracy** – Correctness of quantitative results compared to ground-truth data.  
2. **Decision-Making Support** – Usefulness of narrative insights, scored by:  
   - Topic coverage  
   - Consistency of recommendations  
   - Value-add insights  
   - Specificity of advice  

---

## 📊 Results Summary  

| System | Numeric Accuracy | Decision Support | Observations |
|:--|:--|:--|:--|
| **Baseline Model** | Moderate | **Highest (3/4 scenarios)** | Most coherent and actionable narratives. |
| **PEER System** | Very Low (0% in some tests) | Weak | Underperformed due to coordination complexity. |
| **PEER_ablation** | **Highest (100% in one test)** | Moderate | Best quantitative accuracy; simpler was more robust. |

---

## 🧠 Key Insights  

- **Multi-agent systems are powerful but fragile.**  
  Coordination and orchestration are harder than reasoning itself.  

- **Simplicity outperforms complexity in reliability.**  
  A single, well-guided model can be more useful than a complex but error-prone system.  

- **AI evaluation agents are a new frontier.**  
  Automated judging and report evaluation could form the basis of **AI Quality Assurance (AI-QA)** pipelines.  

---

## 🚀 Strategic Implications  

- **Market need for orchestration platforms** that manage agent coordination, validation, and quality assurance.  
- **Human-AI collaboration** remains essential — the best systems blend automation with human oversight.  
- **Evaluator agents** may become standard in enterprise AI governance frameworks.  

---

## 🧰 Technologies & Tools  

- **Language Models:** GPT-based reasoning engines  
- **Frameworks:** Custom PEER multi-agent orchestration  
- **Synthetic Data Generation:** AI-generated financial datasets  
- **Evaluation:** Automated scoring via referee-agent system  

---

