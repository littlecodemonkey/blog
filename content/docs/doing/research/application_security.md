---
description : "Application Security"
date : "2021-11-23"
tags : [
    "Research",
]
categories : [
    "Research",
    "Cybersecurity",
]
---

# Application Security
Book I am writing on application security.

- Training
  - Training Employees
    - Designing Security Trainings

- Requirements   
  - Software Requirements
    - SDLC
  - Regulation (PCI/HIPPA/SOC/GDPR/CDPA)
  - Prioritization
    - Identifying Stakeholders
    - Prioritizing Projects with Security Concerns

- Design 
  - Best Practices for Design
  - Risk Analysis: Application Threat Modeling
    - DREAD
    - STRIDE
    - Risk Matrix

- Implementation (Coding)
  - Implementation Guidelines
  - Secure coding practices
  - Code Reviews
  - OWASP Secure Headers Project

- Verification (Testing) 
  - Verification Guidelines
  - SAST Testing
    - SonarQube
    - Bandit
    - Gosec
    - npm
  - DAST Testing
    - Burp
    - OWASP ZAP
    - Nikto
  - False Positives
  - Third Party Library Testing

- Release
  - Release Guidelines
  - CI/CD Pipelines - Release code securely

- Response
  - Incident Response

- Common web, and mobile application vulnerabilities 
  - OWASP Top 10 Web App Vulns
    - A1:2017-Injection
    - A2:2017-Broken Authentication
    - A3:2017-Sensitive Data Exposure
    - A4:2017-XML External Entities (XXE)
    - A5:2017-Broken Access Control
    - A6:2017-Security Misconfiguration
    - A7:2017-Cross-Site Scripting (XSS)
    - A8:2017-Insecure Deserialization
    - A9:2017-Using Components with Known Vulnerabilities
    - A10:2017-Insufficient Logging & Monitoring
  - OWASP Top 10 Mobile App Vulns
    - M1: Improper Platform Usage
    - M2: Insecure Data Storage
    - M3: Insecure Communication
    - M4: Insecure Authentication
    - M5: Insufficient Cryptography
    - M6: Insecure Authorization
    - M7: Client Code Quality
    - M8: Code Tampering
    - M9: Reverse Engineering
    - M10: Extraneous Functionality
  - OWASP API Top Ten Vulns
  - Project - Vulnerable web application
  - Test

- Common cloud and container application vulnerabilities
  - Cloud standards
  - IAM Roles
  - DDOS
  - Kubernetes
    - Misconfiguration concerns
    - Common security mistakes
