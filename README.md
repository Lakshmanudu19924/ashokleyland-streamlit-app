# 🚀 Gearbox Machine Shop Efficiency Improvement System  
### (Ashok Leyland Internship Project)

🔗 **Live Application**: https://ashokleyland-app.streamlit.app  
📦 **GitHub Repository**: https://github.com/Lakshmanudu19924/ashokleyland-streamlit-app  

---

## 📌 Project Overview

This project focuses on **improving operational efficiency in the Gearbox Machine Shop at Ashok Leyland** using **data analytics, automated planning logic, and a Streamlit-based web application**.

The system dynamically processes production, inventory, and planning data from Excel inputs to:
- Optimize gearbox production planning
- Detect inventory shortages or surplus
- Automate priority-based decision-making
- Improve Work-In-Progress (WIP) scheduling
- Reduce manual intervention and planning errors

---

## 🏭 Problem Statement

Gearbox production involves:
- Complex multi-level assemblies
- Dependency on child parts
- Weekly and daily production variations
- Inventory mismatch and planning delays

Manual tracking leads to:
- Incorrect stock deductions
- Delayed decisions
- Inefficient resource utilization

This system solves these issues using **data-driven automation**.

---

## 🎯 Key Objectives

- Automate inventory and production calculations
- Dynamically adjust weekly and monthly MPS plans
- Identify child-part deficits and alternates
- Improve WIP visibility and priority handling
- Enable planners to make faster, accurate decisions

---

## 🧠 System Features

### 🔹 Excel-Driven Analytics
- Upload Excel files directly via UI
- Supports XLSX and XLS formats (up to 200MB)

### 🔹 Additional Calculations Module
- Monthly GB Requirement After Opening Stock
- GB Requirement for Balance Month
- Made Here (MH) Parts Calculation
- Priority Sheet (WIP-based prioritization)

### 🔹 Matched Set Analysis
- Against Tentative Plan
  - With Alternate
  - Without Alternate
- Against MPS (2 Weeks)
  - With Alternate
  - Without Alternate
- Against MPS (4 Weeks)
  - With Alternate
  - Without Alternate

### 🔹 Norms Master
- Color-coded manpower (MH) status
- Identifies bottlenecks and overloads
- Improves monitoring and planning clarity

---

## 🧩 Decision Automation Logic

- Child part deficit detection
- Alternate part identification
- WET inventory-based grinding recommendations
- Heat treatment vs soft machining decision logic
- Priority-based matched set generation

---

## 🛠️ Technology Stack

| Layer        | Technology |
|-------------|------------|
| Frontend    | Streamlit |
| Backend     | Python 3.11 |
| Data        | Excel (OpenPyXL, Pandas) |
| Visualization | Streamlit UI |
| Deployment  | Streamlit Community Cloud |
| Version Control | Git & GitHub |

---

## 🏗️ System Architecture

- **Frontend**: Streamlit Web UI
- **Processing Layer**: Business logic for planning & inventory
- **Database Layer**: Excel-based structured data handling
- **Users**:
  - Production Planner
  - Inventory Manager
  - QA Team
  - Suppliers (decision support)

---

## 📊 Outputs Generated

- Dynamic weekly and monthly production plans
- Inventory surplus/deficit reports
- Priority-based WIP scheduling
- Man-hour (MH) utilization tracking
- Downloadable Excel outputs

---

## 👨‍💻 My Role (Intern Contribution)

**Gurrapu Lakshmanudu**  
B.Tech – Computer Science & Engineering  
Vel Tech University  

### Responsibilities:
- UI design using Streamlit
- Prototype design and implementation
- Excel data processing logic
- Functional module integration
- Deployment and testing

---

## 🏢 Internship Details

- **Organization**: Ashok Leyland, Ennore Unit
- **Domain**: Data Analytics & Software Applications
- **Duration**: Nov 2024 – Apr 2025
- **Project Type**: Industrial Internship + Patent-Oriented Work

---

## 📌 How to Run Locally

```bash
py -3.11 -m pip install -r requirements.txt
py -3.11 -m streamlit run main.py
