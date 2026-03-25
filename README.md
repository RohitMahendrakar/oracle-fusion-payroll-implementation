# 💼 Oracle Fusion Payroll Implementation Project (US LDG)

## 📌 Project Overview
This repository contains a comprehensive **end-to-end Oracle Fusion Payroll implementation** focused on the **United States Legislative Data Group (US LDG)**.

The project demonstrates real-world payroll configuration including legal structures, payroll definitions, costing, payment processing, elements, and balances. It simulates a production-like payroll environment using Oracle Fusion HCM.

All configurations are supported with **detailed screenshots** for better understanding and validation.

---

## 🎯 Project Objectives
- Configure a complete payroll system in Oracle Fusion
- Understand payroll architecture and dependencies
- Implement US-specific statutory and compliance requirements
- Enable payroll processing lifecycle from setup to execution
- Gain hands-on experience with enterprise payroll configuration

---

## 🌎 Scope of Implementation
- **Region:** United States (US LDG)
- **Module:** Oracle Fusion HCM - Payroll
- **Type:** Functional Implementation (Configuration-based)
- **Use Case:** Enterprise Payroll Setup Simulation

---

## 🧱 Payroll Architecture Overview
The project follows a structured payroll setup approach:

1. Enterprise & Legal Structure  
2. Legislative & Compliance Setup  
3. Banking & Payment Infrastructure  
4. Payroll Core Configuration  
5. Elements & Balances  
6. Employee-Level Configuration  
7. Payroll Processing Readiness  

---

## 🧩 Detailed Configuration Steps

### 1️⃣ Introduction to Payroll Management
- Overview of Payroll Lifecycle (Pre-payroll, Payroll Run, Post-payroll)
- Payroll Relationships and Assignments
- Integration with Core HR modules
- Payroll flow patterns and process configuration

---

### 2️⃣ Manage Key Flexfields (KFF)

#### 🔹 People Group Key Flexfield
- Used to categorize employees for payroll processing
- Helps in defining payroll eligibility and grouping logic

#### 🔹 Cost Allocation Key Flexfield
- Defines costing segments such as:
  - Company
  - Cost Center
  - Department
  - Account
- Enables accurate financial tracking of payroll expenses

---

### 3️⃣ Legal Structures Setup

#### 🔹 Legal Entity Configuration
- Creation of Legal Employer
- Assignment of Payroll Statutory Unit (PSU)
- Linking with Legislative Data Group (LDG)

#### 🔹 Legislative Data Group (LDG)
- Defines country-specific payroll rules
- Controls taxation and compliance logic

#### 🔹 Payroll Statutory Unit (PSU)
- Responsible for payroll processing and statutory reporting

#### 🔹 Legal Jurisdictions
- Defines geographical tax applicability (State, County, City)

#### 🔹 Legal Authorities
- Government bodies (IRS, State Tax Authorities)

#### 🔹 Legal Reporting Unit (LRU / TRU)
- Tax reporting entity for payroll submissions

#### 🔹 Registrations
- Legal Entity Registration (Federal/State IDs)
- LRU/TRU Registration (Tax IDs)

#### 🔹 HCM Information Setup
- Payroll-related attributes configured at LRU level

---

### 4️⃣ Configure Payroll Legislations
- Define country-specific payroll rules
- Configure tax reporting and statutory compliance
- Enable US-specific payroll features

---

### 5️⃣ Feature Configuration
- Select appropriate country/territory
- Enable payroll features and licenses
- Activate required payroll functionalities

---

### 6️⃣ Banking Infrastructure Setup

#### 🔹 Manage Banks
- Creation of bank institutions

#### 🔹 Manage Bank Branches
- Define branch-level details

#### 🔹 Manage Bank Accounts
- Employer bank accounts for payroll disbursement

---

### 7️⃣ Payment Configuration

#### 🔹 Organization Payment Methods
- Define payment types (Check, EFT, Direct Deposit)

#### 🔹 Third-Party Setup
- Individuals or organizations receiving payments
- Examples:
  - Tax authorities
  - Benefits providers

#### 🔹 Third-Party Payment Methods
- Configure payment rules for deductions

---

### 8️⃣ Consolidation Groups
- Logical grouping of payrolls
- Used during payroll run processing

---

### 9️⃣ Payroll Definition
- Define payroll name and frequency:
  - Monthly
  - Bi-weekly
- Assign LDG and PSU
- Configure time definitions and calendars

---

### 🔟 Elements Configuration

#### 🔹 Element Creation
- Earnings (Salary, Bonus)
- Deductions (Tax, Insurance)

#### 🔹 Element Classifications
- Primary classification (Earnings/Deductions)
- Secondary classifications

#### 🔹 Input Values
- Define user inputs (Amount, Hours, Rate)

#### 🔹 Eligibility Profiles
- Control which employees receive elements

---

### 1️⃣1️⃣ Balance Definitions
- Tracks payroll totals such as:
  - Gross Pay
  - Net Pay
  - Tax Deductions
- Used for reporting and compliance

---

### 1️⃣2️⃣ Event Groups
- Defines payroll processing triggers
- Controls event-based payroll actions

---

### 1️⃣3️⃣ Salary Basis Configuration
- Define salary structures:
  - Hourly
  - Annual
- Link salary basis with payroll elements

---

### 1️⃣4️⃣ Object Groups
- Logical grouping of payroll components
- Used in batch processing and security

---

### 1️⃣5️⃣ Calculation Cards
- Employee-level payroll configuration
- Includes:
  - Federal Tax Card
  - State Tax Card
- Stores tax filing details and deductions

---

### 1️⃣6️⃣ End-to-End Payroll Readiness
- Employee assignment to payroll
- Validation of payroll inputs
- Payroll run simulation
- Prepayments and payment processing

---

## 🔄 Payroll Process Flow
1. Employee Setup  
2. Element Assignment  
3. Payroll Run  
4. Validation & Error Handling  
5. Prepayments  
6. Payment Processing  
7. Payslip Generation  

---

## 📸 Screenshots
This repository includes screenshots for:

- Legal Entity Setup  
- Payroll Configuration  
- Element Creation  
- Payment Setup  
- Calculation Cards  

📂 Navigate to the `/screenshots` directory for detailed visuals.

---

## 🚀 Key Achievements
- Successfully configured a complete payroll system
- Implemented US statutory compliance setup
- Designed payroll elements and balances
- Enabled end-to-end payroll processing flow
- Built real-time implementation experience

---

## 🧠 Key Learnings
- Oracle Fusion Payroll architecture
- Relationship between LDG, PSU, and Legal Entities
- Importance of payroll elements and balances
- Taxation and compliance configuration
- Real-world payroll processing lifecycle

---

## 🛠️ Tools & Technologies
- Oracle Fusion HCM Cloud
- Oracle Payroll Module
- Functional Setup Manager (FSM)

---

## 📈 Future Enhancements
- Integration with Time & Labor module
- Payroll costing and GL integration
- Advanced reporting using OTBI
- Automation of payroll flows

---

## 🤝 Contribution
This project is created for learning and demonstration purposes.  
Suggestions and improvements are welcome.

---

## 📬 Contact
**Name:** Rohit Anand Mahendrakar  
Feel free to connect for discussions on Oracle Fusion, Payroll, or HCM implementations.

---
