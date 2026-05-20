## Hi there, I'm Simón Monaco 👋

## 🧪 About Me

I'm a QA Automation Engineer Junior based in Argentina, focused on building
end-to-end testing pipelines that integrate modern tools, cloud infrastructure,
and CI/CD automation.

I recently graduated as a Systems Analysis Technician and as a University
Technician in Free Software (ISFDyT 210). I'm looking for my first professional
IT experience in QA Automation or QA Manual roles.

- 🔭 Currently seeking work as QA Automation / QA Manual Engineer
- 🌱 Continuously improving my automation and cloud testing skills
- 🌐 English: C2 (EF SET 76/100) — comfortable in technical environments
- 📫 Reach me at: simonmonaco2001@gmail.com
- 📍 La Plata, Buenos Aires, Argentina

---

## 🚀 Featured Project — Coffee Cart QA Pipeline

Full QA pipeline for [coffee-cart.app](https://coffee-cart.app) integrating
6 testing layers orchestrated by Jenkins, each suite isolated in its own
Docker container, with AWS services simulated via LocalStack.

**10-stage Jenkinsfile:** cleanup → Newman (API) → Cypress (E2E) →
JMeter (performance) → OWASP ZAP (security) → LocalStack init →
Cloud setup → S3 upload → SQS polling → teardown

**AWS architecture:** S3 (reports by suite/date) · Lambda (PASS/FAIL
validation) · DynamoDB (execution history) · SQS (failure queue + DLQ)

→ [qa-repository-coffee-cart](https://github.com/MonacoSimon/qa-repository-coffee-cart)

---

## 🌐 Portfolio

→ https://monacosimon.github.io/interfaz-portfolio/

---

## 🛠 QA Stack

### Testing Tools
![Cypress](https://img.shields.io/badge/Cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Newman](https://img.shields.io/badge/Newman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Apache JMeter](https://img.shields.io/badge/Apache%20JMeter-D22128?style=for-the-badge&logo=apache&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP%20ZAP-000000?style=for-the-badge&logo=owasp&logoColor=white)
![Axe](https://img.shields.io/badge/Axe-663399?style=for-the-badge&logoColor=white)

### CI/CD & Infrastructure
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### Languages & Scripting
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)

### Project Management
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 📂 QA Projects

| Project | Level | Stack |
|---|---|---|
| [Coffee Cart](https://github.com/MonacoSimon/qa-repository-coffee-cart) | ⭐ Main | Jenkins · Docker · Cypress · Newman · JMeter · ZAP · AWS |
| [Juice Shop](https://github.com/MonacoSimon/qa-repository-juice-shop) | Advanced | OWASP ZAP · Docker · Cypress |
| [Product Store](https://github.com/MonacoSimon/qa-repository-product-store) | Advanced | Cypress · Postman · Newman · Docker |
| [API Test Postman](https://github.com/MonacoSimon/qa-repository-api-test-postman) | Intermediate | Postman · Newman |
| [Blaze Demo](https://github.com/MonacoSimon/qa-repository-blaze-demo) | Intermediate | Cypress · E2E |
| [Space and Beyond](https://github.com/MonacoSimon/qa-repository-space-and-beyond) | Basic | Cypress · Manual QA |
| [Web Testing Project](https://github.com/MonacoSimon/qa-web-testing-project) | Initial | Manual QA · Bug reports |