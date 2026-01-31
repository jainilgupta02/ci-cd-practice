# 🚀 CI/CD Practice – DevOps Internship (MS Elevate)

This repository is part of my **GTU 8th Semester Internship** under  
**Microsoft Elevate Program**, powered by **FICE Education**.

I am learning and practicing **CI/CD pipelines using GitHub Actions & YAML**  
with real Dev → Test → Prod workflow simulation.

---

## 🧠 What I’m Learning
- CI/CD fundamentals
- GitHub Actions
- YAML workflows
- Dev, Test, Prod environments
- Python automation scripts
- DevOps best practices
- Real pipeline execution & logs

---

## 📂 Project Structure
```text
ci-cd-practice/
│
├── dev.py # Development stage simulation
├── test.py # Testing stage simulation
├── prod.py # Production deployment simulation
│
└── .github/
└── workflows/
└── main.yml # CI/CD pipeline definition
```

---

## ⚙️ CI/CD Pipeline Flow

```text
Developer Push
      ↓
DEV job  → python dev.py
      ↓
TEST job → python test.py
      ↓
PROD job → python prod.py
