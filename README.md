# 🚀 CI/CD Practice with GitHub Actions

This repository is created as part of my **DevOps & Cloud Computing course (PW Skills)**  
to practice **CI/CD pipelines using GitHub Actions and YAML**.

---

## 📌 What this project demonstrates

- Understanding CI/CD pipeline flow
- Writing YAML workflows
- Dev → Test → Prod stages
- Job dependencies in GitHub Actions
- Python automation in pipelines
- Real-time pipeline logs
- Hands-on DevOps practice

---

## 🏗️ Project Structure
```text
ci-cd-practice/
│
├── dev.py # Development stage script
├── test.py # Testing stage script
├── prod.py # Production stage script
│
└── .github/
└── workflows/
└── main.yml # CI/CD pipeline
```

---

## 🔄 CI/CD Pipeline Flow
DEV → TEST → PROD

### 🔹 Dev Stage
- Simulates environment setup
- Dependency installation
- Developer checks

### 🔹 Test Stage
- Simulates unit testing
- Runs multiple test cases
- Validates code before production

### 🔹 Prod Stage
- Simulates deployment
- Logs deployment time
- Marks application LIVE

---

## ⚙️ Technologies Used

- **GitHub Actions**
- **YAML**
- **Python**
- **Linux (Ubuntu runner)**
- **Git & GitHub**
- **CI/CD concepts**

---

## 📊 Where to see output?

Go to:
GitHub → Actions → Workflow run → Click job → View logs

You will see live output like:
- Development completed
- Tests passed
- Production deployed

---

## 🎓 Learning Outcome

- Learned CI/CD from scratch
- Understood pipeline stages
- Hands-on with GitHub Actions
- Built confidence in DevOps workflows

---

## 👨‍💻 Author

**Jay Gupta**  
DevOps & Cloud Computing Learner  
PW Skills | Microsoft Elevate Intern  

---
⭐ If you find this useful, give it a star!
