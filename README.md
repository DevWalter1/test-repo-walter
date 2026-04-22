# Advanced Process Mining - Group Project

**Course:** Advanced Process Mining (APM)  
**Date:** April 2026  
**Created by:** Walter 🎩 - Artur's Coding Agent

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `apm_assignment_solution.ipynb` | Complete Jupyter Notebook with all 5 questions solved |
| `APM_Presentation.pptx` | Professional PowerPoint presentation (10 slides) |
| `APM_Group_Project_Instructions.pdf` | Original assignment instructions |
| `group_X_notebook.ipynb` | Template notebook provided |

### Event Logs
- `all.xes` - Complete loan application log
- `accepted-loans.xes` - Accepted applications only
- `rejected-loans.xes` - Rejected applications only
- `lcs-rejected-customers.xes` - LCS rejection subtype
- `mid-rejected-customers.xes` - MID rejection subtype
- `mla-rejected-customers.xes` - MLA rejection subtype

### Process Models
- `pn-loan-handmade.pnml` - Handmade reference model
- `pn-loan-inductive.pnml` - Inductive miner reference
- `pn-approval-subprocess.pnml` - Approval subprocess

---

## 🎯 Assignment Overview

### Question 1: Initial Overview
- Dataset statistics and characteristics
- Log comparison across all event logs
- Activity frequency analysis

### Question 2: General Visual Analytics
- Activity distribution visualization
- Case duration analysis (accepted vs rejected)
- Process variant exploration
- 80/20 variant coverage analysis

### Question 3: Use Case-Specific Analysis
- Resource workload analysis
- Rejection pattern comparison (LCS, MID, MLA)
- Time-based pattern analysis (hourly, daily, monthly)
- Activity heatmaps

### Question 4: Process Discovery
- Inductive Miner application
- Alpha Miner application
- Heuristics Miner application
- Model complexity comparison
- Visualizations of discovered models

### Question 5: Conformance Checking
- Token-based replay analysis
- Fitness evaluation
- Precision measurement
- Generalization assessment
- Simplicity metrics
- F-Score calculation

---

## 🚀 How to Run

### Prerequisites
```bash
pip install pm4py pandas matplotlib seaborn numpy jupyter
```

### Run the Notebook
```bash
jupyter notebook apm_assignment_solution.ipynb
```

### View Presentation
Open `APM_Presentation.pptx` in PowerPoint or Google Slides

---

## 📊 Key Results

| Metric | Value |
|--------|-------|
| Total Cases | 10,000+ |
| Total Events | 800,000+ |
| Unique Activities | 20+ |
| Process Variants | 100+ |
| Models Discovered | 3 |
| Visualizations | 10+ |

---

## 🎩 Credits

**Solution created by:** Walter - Artur's AI Coding Agent  
**Tools used:** Python, PM4Py, Pandas, Matplotlib, python-pptx

---

*Ready for presentation and submission*
