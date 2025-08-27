# 🔐 IAM SSO + MFA Lab

Hands-on Identity & Access Management (IAM) projects to showcase **engineering skills** in authentication, SSO, and security automation.

---

## 📌 Projects Included

### 1) SSO Integration Lab
- Flask web app with **Okta OIDC + SAML** integrations  
- Demonstrates:
  - OIDC Authorization Code flow
  - SAML 2.0 AuthnRequest/Response
  - Metadata endpoints
  - User session & claims display

🔗 [Setup Guide](sso-integration-lab/README.md)  
📄 [SSO Flow Documentation](sso-integration-lab/docs/SSO_Flow.md)

---

### 2) MFA Enforcement Script
- Python scripts using **Okta API** to audit & enforce MFA
- `okta_mfa_audit.py` → generates `mfa_report.csv` of enrolled factors
- `okta_mfa_enforce.py` → adds non-MFA users to an “MFA Required” group

🔗 [Setup Guide](mfa-enforcement/README.md)

---

## 🛠️ Tech Stack
- Python (Flask, Requests, Authlib)
- Okta OIDC / SAML / API
- HTML + CSS templates
- dotenv for config

---

## 🚀 Why this repo?
✅ Demonstrates **real IAM engineering tasks**  
✅ End-to-end **SSO integration (OIDC + SAML)**  
✅ **MFA compliance automation** with Okta APIs  
✅ Perfect for interviews & portfolio

---

## 📷 Screenshots
> Add screenshots of:
- OIDC login screen
- Profile claims view
- MFA report CSV

---

## 🧑‍💻 Author
**Your Name** – *Identity & Access Management Engineer*  
