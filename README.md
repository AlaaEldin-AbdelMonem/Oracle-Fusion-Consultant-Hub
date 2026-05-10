# Oracle-Fusion-Consultant-Hub 🚀

 
**A specialized knowledge base for Oracle HCM Cloud & Technical Professionals. Centralizing SQL, HDL, OIC patterns, and core admin guides for Security, Approvals, and Platform configurations.**

---

## 📚 Repository Scope
This hub focuses on the **Human Capital Management (HCM)** suite and the **Common Technical Foundation** required to run it. It serves as a toolkit for consultants to deploy faster and more securely.

## 📂 Structure

```text
├── /HCM-Modules             # Functional & Technical assets per module
│   ├── /Global-HR           # Core HR, Workforce structures
│   ├── /Payroll             # Elements, Costing, Fast Formulas
│   ├── /Recruiting          # ORC, Candidate flows, Job boards
│   ├── /Talent-Management   # Goals, Performance, Profiles
│   └── /Absence-Time        # Accruals, Time entry patterns
│
├── /Common-Platform         # The Admin & Security "Engine"
│   ├── /Security-RBAC       # Custom Roles, Data Security Policies, Privileges
│   ├── /Approvals-BPM       # Transaction Console, BPM Worklist, Custom Rules
│   ├── /Lookups-DFF         # Custom Lookups, Flexfields (DFF/EFF/KFF)
│   └── /Notifications       # Alert Composer, BI Publisher email templates
│
├── /Technical-Toolbox       # Automation & Data movement
│   ├── /SQL-Library         # BIP Queries for HCM tables (PER, PAY, HR)
│   ├── /OIC-Integrations    # Integration patterns (REST/SOAP/Atom Feeds)
│   └── /HDL-HSDL            # Data Loader templates for mass updates
└── /Docs                    # Implementation checklists & Best practices
```

## 🚀 How to Use
1. **Security Audit:** Check `/Common-Platform/Security-RBAC` for SQL queries to audit who has "sensitive" privileges.
2. **Approval Debugging:** See `/Common-Platform/Approvals-BPM` for common logic used to route transfers to the "Area of Responsibility" (AOR).
3. **HCM Extracts:** Navigate to `/Technical-Toolbox/SQL-Library` for the specific table joins needed for employee salary history.

## 🤝 Contributing
Have a high-performing SQL query or a tricky Approval rule?
1. **Fork** the repo.
2. Add your script with a brief header comment.
3. Open a **Pull Request**.

## 📄 License
Licensed under the **MIT License**. Use freely in your projects, but please keep the attribution.

## ⚠️ Disclaimer
Not affiliated with Oracle. **Always test scripts in a Sandbox/Test environment first.**
